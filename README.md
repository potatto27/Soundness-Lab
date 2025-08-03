<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/4fe68db3-1d7f-4edc-964a-c66b33c54d77" />

# SOUNDNESS CLI KEY IMPORT GUIDE
## Step by step guide to importing keys in the soundness cli tool.


## 📦STEP 1 : Installation Commands:
```sudo apt update && sudo apt upgrade -y```

` curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash `

```source ~/.bashrc```

```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh```

```source $HOME/.cargo/env```

```soundnessup install```

```soundnessup update```


## 🔐 Import Old Key Using Your Mnemonic Phrase:

### If you have your old 24-word phrase, use this to restore your key
```soundness-cli import-key --name my-key --mnemonic "your 24 words phrase"```

## 🆕 Generate a New Key:
### Try this command when you want creat a new kye.

```soundness-cli generate-key --name my-key```

#### Note: If you want to use your own name as generated key name ,you can modify it by replace "my-key" to "xyz(your name or anything you want)-key"

## 📋 Listing Key Pairs:
### To view all stored key pairs and their names, run this:

```soundness-cli list-keys```

#### If you need any other information ,simply ask in Soundness Discord Channel.

