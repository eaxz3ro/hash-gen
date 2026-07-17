## **Features**

### **Core Functionalities**

| Feature | Description |
|---------|-------------|
| **MD5 Hashing** | Generate 128-bit MD5 hashes from input data |
| **SHA-256 Hashing** | Generate 256-bit SHA-256 hashes from input data |
| **Rainbow Table Generation** | Create precomputed hash tables for password cracking |
| **AES-128 Encryption** | Encrypt output files using AES-128 |
| **AES-128 Decryption** | Decrypt encrypted files with correct key |

### **User Experience Features**

- **Cross-Platform** - Works on Linux, Windows, and macOS
- **Command-Line Interface** - Simple and efficient terminal-based interaction
- **User Choice** - Select between MD5, SHA-256, encryption, or decryption
- **File-Based Processing** - Read from input.txt and write to output.txt
- **Unique Key Generation** - Random encryption keys generated each time

---

## **Technologies Used**

### **Programming Language**

C

### **Libraries & Headers**

| Header | Purpose |
|--------|---------|
| `stdio.h` | Input and output operations |
| `stdlib.h` | Memory allocation and process control |
| `string.h` | String manipulation |
| `time.h` | Random number generation seeding |
| `stdint.h` | Fixed-size integer data types |

---

## **Usage**

Before launching, ensure you have GCC compiler installed.

### **Compile the Program**

```bash
gcc generator.c -o generator
```

### **Launch Application**

```bash
./generator
```

### **1. MD5 Hashing**

1. Create `input.txt` file with passwords (one per line)
2. Run the program
3. Enter `1` when prompted
4. Hashes are written to `output.txt`

### **2. SHA-256 Hashing**

1. Create `input.txt` file with passwords (one per line)
2. Run the program
3. Enter `2` when prompted
4. Hashes are written to `output.txt`

### **3. AES-128 Encryption**

1. Run the program
2. Enter `3` when prompted
3. Encryption key is displayed
4. File is encrypted as `encrypted.bin`

### **4. AES-128 Decryption**

1. Run the program
2. Enter `4` when prompted
3. Enter the encryption key when requested
4. File is decrypted as `decrypted.txt`
