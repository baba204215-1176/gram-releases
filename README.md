# Gram releases

यह भंडार सिर्फ़ Gram ऐप की तैयार APK फ़ाइल रखता है, ताकि फ़ोन में लगा Gram ख़ुद नया संस्करण देखकर अपडेट कर सके।
इसमें कोई source code, चाबी या पासवर्ड नहीं है।

This repository only holds the latest Gram release APK (`Gram.apk`) and `version.json`, which the app reads to offer an in-app update.
It contains no source code, no signing key and no secrets. The app verifies the SHA-256 and the signing certificate before installing.

## सीधा डाउनलोड / Direct download

सबसे नया Gram (हमेशा यही लिंक): https://raw.githubusercontent.com/baba204215-1176/gram-releases/main/Gram-latest.apk

`Gram-latest.apk` is always a byte-for-byte copy of the newest `Gram-v<N>.apk` (arm64).
