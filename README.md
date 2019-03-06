-------------------------------------------------------------------------------

--- Testing wyhash "wyhash, 64-bit"



[[[ Sanity Tests ]]]



Verification value 0xA41FB14D : PASS

Running sanity check 1    ..........PASS

Running AppendedZeroesTest..........PASS



[[[ Speed Tests ]]]



Bulk speed test - 262144-byte keys

Alignment  7 -  2.181 bytes/cycle - 6239.99 MiB/sec @ 3 ghz

Alignment  6 -  2.238 bytes/cycle - 6402.25 MiB/sec @ 3 ghz

Alignment  5 -  2.238 bytes/cycle - 6402.22 MiB/sec @ 3 ghz

Alignment  4 -  2.238 bytes/cycle - 6402.20 MiB/sec @ 3 ghz

Alignment  3 -  2.238 bytes/cycle - 6402.27 MiB/sec @ 3 ghz

Alignment  2 -  2.238 bytes/cycle - 6402.17 MiB/sec @ 3 ghz

Alignment  1 -  2.238 bytes/cycle - 6402.33 MiB/sec @ 3 ghz

Alignment  0 -  2.266 bytes/cycle - 6483.45 MiB/sec @ 3 ghz

Average      -  2.234 bytes/cycle - 6392.11 MiB/sec @ 3 ghz



Small key speed test -    1-byte keys -    16.00 cycles/hash

Small key speed test -    2-byte keys -    16.00 cycles/hash

Small key speed test -    3-byte keys -    17.00 cycles/hash

Small key speed test -    4-byte keys -    16.00 cycles/hash

Small key speed test -    5-byte keys -    17.00 cycles/hash

Small key speed test -    6-byte keys -    17.00 cycles/hash

Small key speed test -    7-byte keys -    18.00 cycles/hash

Small key speed test -    8-byte keys -    23.00 cycles/hash

Small key speed test -    9-byte keys -    26.00 cycles/hash

Small key speed test -   10-byte keys -    26.31 cycles/hash

Small key speed test -   11-byte keys -    26.33 cycles/hash

Small key speed test -   12-byte keys -    26.00 cycles/hash

Small key speed test -   13-byte keys -    26.32 cycles/hash

Small key speed test -   14-byte keys -    26.30 cycles/hash

Small key speed test -   15-byte keys -    26.26 cycles/hash

Small key speed test -   16-byte keys -    26.15 cycles/hash

Small key speed test -   17-byte keys -    30.00 cycles/hash

Small key speed test -   18-byte keys -    30.00 cycles/hash

Small key speed test -   19-byte keys -    30.00 cycles/hash

Small key speed test -   20-byte keys -    30.00 cycles/hash

Small key speed test -   21-byte keys -    30.00 cycles/hash

Small key speed test -   22-byte keys -    30.00 cycles/hash

Small key speed test -   23-byte keys -    30.00 cycles/hash

Small key speed test -   24-byte keys -    30.00 cycles/hash

Small key speed test -   25-byte keys -    33.97 cycles/hash

Small key speed test -   26-byte keys -    33.98 cycles/hash

Small key speed test -   27-byte keys -    33.78 cycles/hash

Small key speed test -   28-byte keys -    33.96 cycles/hash

Small key speed test -   29-byte keys -    33.75 cycles/hash

Small key speed test -   30-byte keys -    33.78 cycles/hash

Small key speed test -   31-byte keys -    33.79 cycles/hash

Average                                    26.667 cycles/hash



[[[ Differential Tests ]]]



Testing 8303632 up-to-5-bit differentials in 64-bit keys -> 64 bit hashes.

1000 reps, 8303632000 total tests, expecting 0.00 random collisions..........

0 total collisions, of which 0 single collisions were ignored



Testing 11017632 up-to-4-bit differentials in 128-bit keys -> 64 bit hashes.

1000 reps, 11017632000 total tests, expecting 0.00 random collisions..........

0 total collisions, of which 0 single collisions were ignored



Testing 2796416 up-to-3-bit differentials in 256-bit keys -> 64 bit hashes.

1000 reps, 2796416000 total tests, expecting 0.00 random collisions..........

0 total collisions, of which 0 single collisions were ignored





[[[ Avalanche Tests ]]]



Testing  32-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.870000%

Testing  40-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.778667%

Testing  48-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.686000%

Testing  56-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.649333%

Testing  64-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.702000%

Testing  72-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.878667%

Testing  80-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.769333%

Testing  88-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.751333%

Testing  96-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.622667%

Testing 104-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.693333%

Testing 112-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.662667%

Testing 120-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.781333%

Testing 128-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.671333%

Testing 136-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.722000%

Testing 144-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.703333%

Testing 152-bit keys ->  64-bit hashes,   300000 reps.......... worst bias is 0.764000%



[[[ Keyset 'Cyclic' Tests ]]]



Keyset 'Cyclic' - 8 cycles of 8 bytes - 10000000 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  39 - 0.049%



Keyset 'Cyclic' - 8 cycles of 9 bytes - 10000000 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  19-bit window at bit  16 - 0.026%



Keyset 'Cyclic' - 8 cycles of 10 bytes - 10000000 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  55 - 0.024%



Keyset 'Cyclic' - 8 cycles of 11 bytes - 10000000 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  29 - 0.055%



Keyset 'Cyclic' - 8 cycles of 12 bytes - 10000000 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  27 - 0.026%





[[[ Keyset 'TwoBytes' Tests ]]]



Keyset 'TwoBytes' - up-to-4-byte keys, 652545 total keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  16-bit window at bit   3 - 0.151%



Keyset 'TwoBytes' - up-to-8-byte keys, 5471025 total keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  32 - 0.056%



Keyset 'TwoBytes' - up-to-12-byte keys, 18616785 total keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  30 - 0.022%



Keyset 'TwoBytes' - up-to-16-byte keys, 44251425 total keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  30 - 0.005%



Keyset 'TwoBytes' - up-to-20-byte keys, 86536545 total keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  10 - 0.004%





[[[ Keyset 'Sparse' Tests ]]]



Keyset 'Sparse' - 32-bit keys with up to 6 bits set - 1149017 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  17-bit window at bit  31 - 0.073%



Keyset 'Sparse' - 40-bit keys with up to 6 bits set - 4598479 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  19-bit window at bit  21 - 0.042%



Keyset 'Sparse' - 48-bit keys with up to 5 bits set - 1925357 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  18-bit window at bit  41 - 0.076%



Keyset 'Sparse' - 56-bit keys with up to 5 bits set - 4216423 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  19-bit window at bit  26 - 0.063%



Keyset 'Sparse' - 64-bit keys with up to 5 bits set - 8303633 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit   3 - 0.044%



Keyset 'Sparse' - 96-bit keys with up to 4 bits set - 3469497 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  19-bit window at bit  58 - 0.063%



Keyset 'Sparse' - 256-bit keys with up to 3 bits set - 2796417 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  19-bit window at bit  53 - 0.071%



Keyset 'Sparse' - 2048-bit keys with up to 2 bits set - 2098177 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  17-bit window at bit   3 - 0.066%





[[[ Keyset 'Combination Lowbits' Tests ]]]



Keyset 'Combination' - up to 8 blocks from a set of 8 - 19173960 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  11 - 0.011%





[[[ Keyset 'Combination Highbits' Tests ]]]



Keyset 'Combination' - up to 8 blocks from a set of 8 - 19173960 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  32 - 0.014%





[[[ Keyset 'Combination 0x8000000' Tests ]]]



Keyset 'Combination' - up to 20 blocks from a set of 2 - 2097150 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  17-bit window at bit  53 - 0.046%





[[[ Keyset 'Combination 0x0000001' Tests ]]]



Keyset 'Combination' - up to 20 blocks from a set of 2 - 2097150 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  18-bit window at bit  45 - 0.074%





[[[ Keyset 'Combination Hi-Lo' Tests ]]]



Keyset 'Combination' - up to 6 blocks from a set of 15 - 12204240 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit   0 - 0.024%





[[[ Keyset 'Window' Tests ]]]



Keyset 'Windowed' - 128-bit key,  20-bit window - 128 tests, 1048576 keys per test

Window at   0 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   1 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   2 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   3 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   4 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   5 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   6 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   7 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   8 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at   9 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  10 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  11 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  12 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  13 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  14 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  15 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  16 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  17 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  18 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  19 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  20 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  21 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  22 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  23 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  24 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  25 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  26 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  27 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  28 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  29 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  30 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  31 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  32 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  33 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  34 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  35 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  36 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  37 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  38 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  39 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  40 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  41 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  42 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  43 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  44 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  45 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  46 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  47 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  48 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  49 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  50 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  51 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  52 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  53 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  54 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  55 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  56 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  57 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  58 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  59 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  60 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  61 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  62 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  63 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  64 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  65 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  66 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  67 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  68 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  69 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  70 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  71 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  72 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  73 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  74 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  75 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  76 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  77 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  78 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  79 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  80 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  81 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  82 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  83 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  84 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  85 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  86 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  87 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  88 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  89 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  90 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  91 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  92 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  93 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  94 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  95 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  96 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  97 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  98 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at  99 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 100 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 101 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 102 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 103 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 104 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 105 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 106 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 107 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 108 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 109 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 110 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 111 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 112 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 113 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 114 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 115 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 116 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 117 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 118 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 119 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 120 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 121 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 122 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 123 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 124 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 125 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 126 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 127 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Window at 128 - Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)



[[[ Keyset 'Text' Tests ]]]



Keyset 'Text' - keys of form "Foo[XXXX]Bar" - 14776336 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit   6 - 0.025%



Keyset 'Text' - keys of form "FooBar[XXXX]" - 14776336 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit   1 - 0.019%



Keyset 'Text' - keys of form "[XXXX]FooBar" - 14776336 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  20-bit window at bit  52 - 0.033%





[[[ Keyset 'Zeroes' Tests ]]]



Keyset 'Zeroes' - 65536 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  13-bit window at bit   8 - 0.611%





[[[ Keyset 'Seed' Tests ]]]



Keyset 'Seed' - 1000000 keys

Testing collisions   - Expected     0.00, actual     0.00 ( 0.00x)

Testing distribution - Worst bias is the  17-bit window at bit  36 - 0.066%







Input vcode 0x00000001, Output vcode 0x00000001, Result vcode 0x00000001

Verification value is 0x00000001 - Testing took 773.839558 seconds

-------------------------------------------------------------------------------
