# Project-1
# What are Channels and Kernels
![Image of Yaktocat](https://i2.wp.com/i.imgur.com/z2RHZnH.png)
###### Please refer above image.

## Channels
If the whole image is a set and individual collered balls as entities of that set
looking to one individual ball as feature and channel holds all the details of similar balls.
Example a channel can map all red balls ignoring all other color balls from the image.

## Kernels
Kernal is a matrix to identify that individual entities from the image for example round curved edgeg in thr above image.

## Why should we only (well mostly) use 3x3 Kernels?
Basically 3x3 Kernal is used because using this 3x3 Kerels we can map surrounding features as left, right, top and bottom.

## How many times do we need to perform 3x3 convolution operation to reach 1x1 from 199x199 
We need to perform 99 3x3 convolution operation to reach 1x1 from 199x199 and the calculations are as below.
```
197x197        1
195x195        2
193x193        3
191x191        4
189x189        5
187x187        6
185x185        7
183x183        8
181x181        9
179x179        10
177x177        11
175x175        12
173x173        13
171x171        14
169x169        15
167x167        16
165x165        17
163x163        18
161x161        19
159x159        20
157x157        21
155x155        22
153x153        23
151x151        24
149x149        25
147x147        26
145x145        27
143x143        28
141x141        29
139x139        30
137x137        31
135x135        32
133x133        33
131x131        34
129x129        35
127x127        36
125x125        37
123x123        38
121x121        39
119x119        40
117x117        41
115x115        42
113x113        43
111x111        44
109x109        45
107x107        46
105x105        47
103x103        48
101x101        49
99x99        50
97x97        51
95x95        52
93x93        53
91x91        54
89x89        55
87x87        56
85x85        57
83x83        58
81x81        59
79x79        60
77x77        61
75x75        62
73x73        63
71x71        64
69x69        65
67x67        66
65x65        67
63x63        68
61x61        69
59x59        70
57x57        71
55x55        72
53x53        73
51x51        74
49x49        75
47x47        76
45x45        77
43x43        78
41x41        79
39x39        80
37x37        81
35x35        82
33x33        83
31x31        84
29x29        85
27x27        86
25x25        87
23x23        88
21x21        89
19x19        90
17x17        91
15x15        92
13x13        93
11x11        94
9x9        95
7x7        96
5x5        97
3x3        98
1x1        99
```
