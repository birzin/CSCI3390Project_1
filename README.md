Reif Birzin, Zelig Riyanto, Olivia McCarty

1. k=2:
      xS = 1842609935this_is_a_bitcoin_block_of_10323123_66024292_77898238
      Hash Value: 001ccc9fcef1723057efc1f7817bf60eb338bd3962f0d30a72d1aac269d64d6d
      Time Elapsed: 1s
      Trials: 256
   k=3:
      xS = 332421this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238
      Hash Value: 000c146e90f0b04b85cb43e35bd7686c2c533e64b5aee456711da20d6b654a72
      Time Elapsed: 1s
      Trials: 4,096
   k=4:
      xS = 1800256717this_is_a_bitcoin_block_of_10323123_66024292_77898238
      Hash Value: 00003347cb84d338835c0a94cb07707bf507e0930c84b6d01a97109fbf1a93f8
      Time Elapsed: 2s
      Trials: 65,536
   k=5:
      xS = 1237889526this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238
      Hash Value: 000005ed60d62850ab0a922419b33ea5cb40cba6fce636a7cf754f9d8c1151ba
      Time Elapsed: 2s
      Trials: 1,048,576
   k=6:
      xS = 689470094this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238
      Hash Value: 000000decbddf1b818c3bd135a147a35ec691ea90aae6ca13fb8d552be1e6467
      Time Elapsed: 8s
      Trials: 16,777,216

| Difficulty (k) | xS (Nonce + String) | SHA-256 Hash | Time Elapsed | Trials |
|--------------|------------------------------|------------------------------------------------------------------|--------------|--------------------------|
| 2 | 1842609935this_is_a_bitcoin_block_of_10323123_66024292_77898238 | 001ccc9fcef1723057efc1f7817bf60eb338bd3962f0d30a72d1aac269d64d6d | 1s | 256 (\(16^2\)) |
| 3 | 332421this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 000c146e90f0b04b85cb43e35bd7686c2c533e64b5aee456711da20d6b654a72 | 1s | 4,096 (\(16^3\)) |
| 4 | 1800256717this_is_a_bitcoin_block_of_10323123_66024292_77898238 | 00003347cb84d338835c0a94cb07707bf507e0930c84b6d01a97109fbf1a93f8 | 2s | 65,536 (\(16^4\)) |
| 5 | 1237889526this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 000005ed60d62850ab0a922419b33ea5cb40cba6fce636a7cf754f9d8c1151ba | 2s | 1,048,576 (\(16^5\)) |
| 6 | 689470094this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238 | 000000decbddf1b818c3bd135a147a35ec691ea90aae6ca13fb8d552be1e6467 | 8s | 16,777,216 (\(16^6\)) |

3. 1 Master Node (n2-standard-4)
   2 Worker Nodes (n2-standard-4)
   xS = 689470094this_is_a_bitcoin_block_of_10323123_and_66024292_and_77898238
   Hash Value: 000000decbddf1b818c3bd135a147a35ec691ea90aae6ca13fb8d552be1e6467
   Time Elapsed: 
   Trials: 268,435,456

   We determined the number of trials by taking 16^k. This is the expected number due to the SHA256 hash being in hexadecimal, which uses 16 digits.

4.
