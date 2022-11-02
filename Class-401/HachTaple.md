# hash table
is an implementation of an associative array, a list of key-value pairs that allow you to retrieve a value via a key.
Internally a hash table utilizes a hash function to transform a key value into an index that points to where the value is stored in memory.
Hash tables have fast search, insertion and delete operations.

## Hashing (Hash Function)
In a hash table, a new index is processed using the keys. And, the element corresponding to that key is stored in the index. This process is called hashing.

## Hash Collision
When the hash function generates the same index for multiple keys, there will be a conflict (what value to be stored in that index). This is called a hash collision.

We can resolve the hash collision using one of the following techniques.

Collision resolution by chaining
Open Addressing: Linear/Quadratic Probing and Double Hashing

1. Collision resolution by chaining
In chaining, if a hash function produces the same index for multiple elements, these elements are stored in the same index by using a doubly-linked list.
2. Open Addressing
Unlike chaining, open addressing doesn't store multiple elements into the same slot. Here, each slot is either filled with a single key or left

# different methods to find a good hash function
1. Division Method
2. Multiplication Method
3. Universal Hashing

# Applications of Hash Table
Hash tables are implemented where

1. constant time lookup and insertion is required
2. cryptographic applications
3. indexing data is required
