**1. Clone wallet sources**

```
git clone https://github.com/Steve-sy/mmrcoinwallet.git
```

**2. Modify `CryptoNoteWallet.cmake`**
 
```
set(CN_PROJECT_NAME "mmrcoin-o")
set(CN_CURRENCY_DISPLAY_NAME "MMRcoin")
set(CN_CURRENCY_TICKER "MMR")
```

**3. Set Alternative way is to create git submodule:**

```
git submodule add https://github.com/Steve-sy/mmrcoin-o.git cryptonote
```

Replace URL with git remote repository of your coin.

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
