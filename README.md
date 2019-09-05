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
197x197
195x195
193x193
191x191
189x189
187x187
185x185
183x183
181x181
179x179
177x177
175x175
173x173
171x171
169x169
167x167
165x165
163x163
161x161
159x159
157x157
155x155
153x153
151x151
149x149
147x147
145x145
143x143
141x141
139x139
137x137
135x135
133x133
131x131
129x129
127x127
125x125
123x123
121x121
119x119
117x117
115x115
113x113
111x111
109x109
107x107
105x105
103x103
101x101
99x99
97x97
95x95
93x93
91x91
89x89
87x87
85x85
83x83
81x81
79x79
77x77
75x75
73x73
71x71
69x69
67x67
65x65
63x63
61x61
59x59
57x57
55x55
53x53
51x51
49x49
47x47
45x45
43x43
41x41
39x39
37x37
35x35
33x33
31x31
29x29
27x27
25x25
23x23
21x21
19x19
17x17
15x15
13x13
11x11
9x9
7x7
5x5
3x3
1x1
```
