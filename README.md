# Results

```
test ser/sr.json ... bench:         234 ns/iter (+/- 8)
json: 100 bytes
test ser/de.json ... bench:         343 ns/iter (+/- 3)
test ser/sr.simd-json ... bench:          60 ns/iter (+/- 1)
simd-json: 100 bytes
test ser/de.simd-json ... bench:         462 ns/iter (+/- 1)
simd-json: 100 bytes
test ser/sr.yaml ... bench:        2187 ns/iter (+/- 58)
yaml: 99 bytes
test ser/de.yaml ... bench:        5669 ns/iter (+/- 25)
test ser/sr.ron ... bench:         498 ns/iter (+/- 9)
ron: 91 bytes
test ser/de.ron ... bench:         823 ns/iter (+/- 10)
test ser/sr.bincode ... bench:          35 ns/iter (+/- 0)
bincode: 58 bytes
test ser/de.bincode ... bench:          97 ns/iter (+/- 0)
test ser/sr.msgpack ... bench:          88 ns/iter (+/- 2)
msgpack: 24 bytes
test ser/de.msgpack ... bench:         162 ns/iter (+/- 1)
test ser/sr.cbor ... bench:         137 ns/iter (+/- 9)
cbor: 72 bytes
test ser/de.cbor ... bench:         394 ns/iter (+/- 5)
test ser/sr.postcard ... bench:          44 ns/iter (+/- 0)
postcard: 41 bytes
test ser/de.postcard ... bench:         160 ns/iter (+/- 1)
test ser/ser.flexbuffers ... bench:        1038 ns/iter (+/- 5)
flexbuffers: 41 bytes
test ser/de.flexbuffers ... bench:         700 ns/iter (+/- 9)
test ser/sr.flatbuffers ... bench:         137 ns/iter (+/- 6)
flatbuffers: 104 bytes
test ser/de.flatbuffers ... bench:          87 ns/iter (+/- 0)
test ser/sr.capnproto.unpacked ... bench:         114 ns/iter (+/- 1)
capnproto.unpacked: 96 bytes
test ser/de.capnproto.unpacked ... bench:         282 ns/iter (+/- 2)
test ser/sr.capnproto.packed ... bench:         198 ns/iter (+/- 0)
capnproto.packed: 39 bytes
test ser/de.capnproto.packed ... bench:         380 ns/iter (+/- 2)
test ser/sr.proto3 ... bench:          79 ns/iter (+/- 4)
proto3: 23 bytes
test ser/de.proto3 ... bench:         166 ns/iter (+/- 1)
test ser/sr.abomonation ... bench:           8 ns/iter (+/- 0)
abomonation: 116 bytes
test ser/de.abomonation ... bench:          40 ns/iter (+/- 0)
test ser/sr.speedy ... bench:           9 ns/iter (+/- 0)
speedy: 50 bytes
test ser/de.speedy ... bench:          41 ns/iter (+/- 1)
```
