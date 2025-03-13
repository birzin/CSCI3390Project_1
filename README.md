Reif Birzin, Zelig Riyanto, Olivia McCarty

## (1) 

| Difficulty (k) | xS (Nonce + String) | SHA-256 Hash | Time Elapsed | Trials |
|--------------|------------------------------|------------------------------------------------------------------|--------------|--------------------------|
| 2 | 1842609935this_is_a_bitcoin_block_of_10323123_66024292_77898238 | 001ccc9fcef1723057efc1f7817bf60eb338bd3962f0d30a72d1aac269d64d6d | 1s | 256 (\(16^2\)) |
| 3 | 332421this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 000c146e90f0b04b85cb43e35bd7686c2c533e64b5aee456711da20d6b654a72 | 1s | 4,096 (\(16^3\)) |
| 4 | 1800256717this_is_a_bitcoin_block_of_10323123_66024292_77898238 | 00003347cb84d338835c0a94cb07707bf507e0930c84b6d01a97109fbf1a93f8 | 2s | 65,536 (\(16^4\)) |
| 5 | 1237889526this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 000005ed60d62850ab0a922419b33ea5cb40cba6fce636a7cf754f9d8c1151ba | 2s | 1,048,576 (\(16^5\)) |
| 6 | 689470094this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 000000decbddf1b818c3bd135a147a35ec691ea90aae6ca13fb8d552be1e6467 | 8s | 16,777,216 (\(16^6\)) |

## (2) 
1 Master Node (n2-standard-4) and
2 Worker Nodes (n2-standard-4)
   
| Difficulty (k) | xS (Nonce + String) | SHA-256 Hash | Time Elapsed | Trials |
|--------------|------------------------------|------------------------------------------------------------------|--------------|--------------------------|
7 | 1038768649this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 0000000d73808650ffd76433e2ecbff0d598060a8bad6eacf62ceb1e2ffccdc9 | 122s | 268,435,456 (\(16^7\)) |

  We chose \( 16^7 \) (268,435,456 trials) because each leading zero in the hash reduces the probability of success by a factor of 16. Since SHA-256 hashes are uniformly distributed, the probability of finding a hash with **7 leading zeros** in a single trial is 1/16^7. Therefore, on average, we expect to run \( 16^7 \) trials to find a valid nonce.

## (3)
