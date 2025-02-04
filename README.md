# Title

LRU Cache for system design

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Description](#description)
## Description 
An LRU (Least Recently Used) Cache is a type of data structure that stores a fixed number of elements and automatically removes the least recently used element when the cache reaches its capacity
## Installation
  
``` 
 git clone https://github.com/Ahmedellaithy/LRU-Cache.git
```
## Usage 

- Database Caching: Storing query results to avoid repeated computation and reduce load on databases.
- Web Server Caching: Storing recent API responses or content to speed up repeated requests.

   
## Description
Common Operations:
- Get(key): Retrieves the value of the key if it exists in the cache, otherwise returns -1. Accessing the value updates the item's "recently used" status.
- Put(key, value): Inserts a new key-value pair into the cache. If the cache is full, the least recently used item is evicted.
- Eviction : we use LRU(least recently used so when the cache is full it will remove the least recently key in the cache)

