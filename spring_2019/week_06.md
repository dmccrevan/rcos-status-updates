## Last Week's Accomplishments

This past week I began to implement the saved state feature in Tornado. We chose to use RocksDB for our database. It is an embedded key-value store system. This fits
perfectly for our project since we will be storing minimal amounts of information (user/pass & some other metadata about torrents). I have implemented the basic get/put features and 
began to create more specific functions for our project.

## This Week's Plan

This week I plan on finishing up the saved state module, then I plan to begin implementing a basic user/pass front end to communicate with our database.

## Anything Blocking?

Beginner knowledge with Rust still. Fighting that ownership model.

## Notes

