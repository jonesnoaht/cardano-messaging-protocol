# Messaging Protocol

## Summary

This is a CIP to get a protocol for messaging. Messages can be treated
as NFTs so that pen pals can write messages back and fourth by adding
metadata to the transaction. Eventually, it would be awesome to move
this onto a proof-of-work sidechain or state channel.

Basic structure should contain at least:
 
 1. subject
 2. body
 3. pgp-key address (optional)

It would be best to steal the structure from email or some
well-developed IEEE standard.

## Tasks

 - [ ] Choose a key for the JSON representation of message data.
 - [ ] Solve the problem of encryption (should be easy).
 - [ ] Coordinate with wallet apps to discuss the feasibility of
       monitoring the blockchain for message metadata and sending a
       push alert when one arrives.
