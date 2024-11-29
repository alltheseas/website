---
title: Download Zapstore
date: 2024-08-22
draft: false
---

{{< tabs items="Zapstore for Android, Zapstore CLI" >}}

{{< tab >}}

## 0.1.6 for Android

Download [here](https://cdn.zapstore.dev/356b8022bd1366cf1a16b80a043a26e0f939d3301bba646b3b7732674ccb181a) and install on your device.

{{< callout type="warning" >}}
If this is the first time you install Zapstore on your device, it's important to verify this download.<br><br>
If you are updating, Android will take care of the verification for you.
{{< /callout >}}

### Verification

Are you on a computer? Open a terminal and run `shasum -a 256` on the downloaded file. It should show the following SHA-256 hash:

```text
356b8022bd1366cf1a16b80a043a26e0f939d3301bba646b3b7732674ccb181a 
```

Are you on your Android device? Use [AppVerifier](https://github.com/soupslurpr/AppVerifier/releases/latest) and input the following APK certificate hash:

```
99e33b0c2d07e75fcd9df7e40e886646ff667e3aa6648e1a1160b036cf2b9320
```

For extra assurances, make sure to double check these hashes on [Zapstore's profile on nostr](https://nosta.me/npub10r8xl2njyepcw2zwv3a6dyufj4e4ajx86hz6v4ehu4gnpupxxp7stjt2p8).

{{< /tab >}}

{{< tab >}}
  
## 0.1.2 for Linux and Mac

Download the file and open a terminal to run `shasum -a 256` on the downloaded file. The corresponding SHA-256 hash should match.

### MacOS (arm64)

```
30438f5a972a1c0d7987a0486c76ca12ac9f42571b72f99fe040d146cabc4bb2
```

### Linux (x86_64)

```
0d684425c4bbd3fdecc58f7bf7fc55366d71b8ded9d68b3bbfcb3fcca1072325
```

### Linux (aarch64)

```
a1e80d5ef9845c0977fb593b609b9220b4e0826a11ad88d9575b354439225d98
```

{{< /tab >}}

{{< /tabs >}}