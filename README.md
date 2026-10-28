# Java-Obfuscation-List

This repo lists all currently relevant java obfuscators, including indirect obfuscation techniques that can strengthen a .jar or .apk. Note that this is opinionated and may be bias to some degree.

# Free / Open source
*No currently free/open source obfuscators are relevant in preventing reverse engineering. Most are easy to reverse with ai, but some obfuscators like Aidsfuscator & Ambien might be worthwhile forking.*

# Commercial / Paid
👍 = Good in a chain of obfuscators.
🌟 = Overall solid protection by itself.

| Name | Description |
| -------- | ------- |
| 👍 ZKM (zelix.com) | The most known obfuscator. Known for strong method parameter obfuscation and flow obfuscation. Common in commercial products, since the obfuscator almost never breaks jars. |
| :star2: qProtect (qtechnologies.dev) | Legacy version wasn't the best, but new versions of qProtect are definitely in the top contenders of java obfuscation. One of the goto picks for current security, as qProtect offers state-of-the-art obfuscation techniques. |
| :star2: FlowGuard (flowguard.pro) | Complex obfuscation techniques including fourth-generation flow obfuscation, three-step string encryption and code virtualization. Offers full anti-tampering and native sealing, meaning that your authentication's calls are super secure. You currently have to apply. |
| VMProtect | Code virtualization for native apps. Can be paired with a native transpiler to create a safe environment for authentication. |
| 👍 Themida | High duty code virtualization. Serves the same purpose as VMProtect, but in a more secure way. Features anti-tampering and such features. |
| 👍 JVMTP | Native transpilation for Java. May be good to pair with a code virtualizer. Has it's own virtualization SDK so you can use it with VMP. |
| JNIC | Native transpilation for Java. Places its code in C, and some versions don't allow outside virtualization, but that can usually be fixed with open-source projects. |
