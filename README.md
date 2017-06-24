# AES-ZCM
AES-ZCM (ZHASH with Counter Mode) is for the constrained environment where performance (latency, throughput, power consumption, area) is concerned. It provides parallelizable hardware and software optimization.  

The security goal of the cipher is confidentiality/privacy, integrity/authenticity of plaintext. The implication of the security goal is multi-dimensional bounds, such as time, key length, block length, # of AES calls. As an additional goal, we claim the cipher is capable of providing provable security in the Random Oracle model, and some of the extended security proof, i.e the nonce reuse attacks, the length extension attacks, etc. 
