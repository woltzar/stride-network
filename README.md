<h1 align="center">Stride - Poll Party! </h1>

### Selamlar bugün Stride node testnetine katılacağız. SORULAR İÇİN: https://t.me/StrideTurkish

![image](https://user-images.githubusercontent.com/101149671/180230551-dbc0d5f0-b087-483f-9e7a-95711a820209.png)


# Sistem gereksinimleri, "benim" önerim:


```
4 CPU
8 RAM
160 GB SSD
```

# Kurulum:

```
wget -q -O stride.sh https://api.rues.info/stride.sh && chmod +x stride.sh && sudo /bin/bash stride.sh
```

# Cüzdan oluşturma: (not edin kaydedin)
```
strided keys add <walletName>
```

# Discordan test tokeni alma: https://discord.gg/4B4cbvCh

![image](https://user-images.githubusercontent.com/101149671/180231116-4eaae21a-184c-4204-a3f1-e7ac945e1455.png)

# Validator oluşturma:
```
strided tx staking create-validator \
--amount=9900000ustrd \
--pubkey=$(strided tendermint show-validator) \
--moniker=RuesValidator \
--chain-id=STRIDE-1 \
--commission-rate="0.10" \
--commission-max-rate="0.20" \
--commission-max-change-rate="0.1" \
--min-self-delegation="1" \
--fees=250ustrd \
--gas=200000 \
--from=rues \
--website="http://forum.rues.info/" \
--details="https://linktr.ee/ruesandora0" \
-y
```

# Explorer kontrol: https://stride.explorers.guru/validator/stridevaloper1vm6wnmvxugqj8k6s6d2cktgctc550qaq53jyus

# sorular için: https://t.me/StrideTurkish

# Discorddan role-requestten rol de alabılırsınız.
