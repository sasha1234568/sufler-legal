# Gazelo Privacy Policy

**Revision date: October 20, 2026**

This policy describes the Gazelo app for iPhone and iPad and its companion script library for Mac. It covers data handled by the app operator. Apple services, including iCloud and speech recognition, also process data under Apple’s own terms and privacy policy.

## Operator and contact

Operator: Individual Entrepreneur Hanna Drabysheuskaya, Georgian identification number 305652889.

Address: Georgia, Tbilisi, Vake District, Besarion Zhgenti Street, N 49, Floor 1, Apartment N 20.

Email: [saveo.info@gmail.com](mailto:saveo.info@gmail.com).

## Data the app uses

**Script library.** The app handles script titles and text, folder names, the selected language, reading position, and display settings. It stores this information in a local SwiftData database. If iCloud is enabled and the app’s container is available, the library syncs through the user’s private CloudKit database. These records are stored in the user’s iCloud. The Gazelo operator does not receive a copy of the library on its own server or make scripts publicly accessible.

**App settings.** The selected scrolling mode and certain app preferences are stored in the app’s settings storage on the device.

**Free-time counter.** The app counts time while the teleprompter’s Play mode is active, including voice mode while it is listening for speech. The counter is stored locally in Keychain and the app’s settings on the device and is used only to enforce the free limit. The operator does not receive this counter.

**Purchases and subscriptions.** If a user purchases a monthly subscription, the app uses StoreKit to request the available product from Apple and verify purchase status. Apple processes the payment and Apple Account information under its own terms and privacy policy. The operator does not receive card details or keep a separate payment history on its own server.

**Microphone and speech recognition.** The microphone is used only after the user starts voice scrolling and grants permission. Gazelo streams audio to an Apple system component for recognition and receives recognized text to move the reading position. The app does not create an audio recording or send audio to its own server.

On iOS 26 and later, the app first uses the available Apple Speech streaming technology. In compatible configurations, recognition runs on the device. For some languages, system versions, or when local speech resources are unavailable, the system’s SFSpeechRecognizer may send audio to Apple for recognition. The app also provides up to 100 contextual words from the script to the system recognizer to improve accuracy. As a result, when voice scrolling is used, audio, contextual words, and recognition results may be processed by Apple according to Apple’s terms and the device settings. On-device processing depends on iOS, language, and the installed speech model.

## Who receives data

Gazelo does not use its own server, advertising networks, third-party analytics, or account registration. The free-time counter is stored only on the device. Subscription purchases and status checks use Apple StoreKit; Apple processes payment data. Script data is sent to iCloud only to sync privately between the user’s devices. Audio and contextual words may be sent to Apple systems only when voice scrolling is used, as described above. Apple’s [iCloud and CloudKit terms](https://www.apple.com/legal/privacy/) and [Privacy Policy](https://www.apple.com/legal/privacy/) govern Apple’s processing.

If a user emails the operator, the operator receives the sender’s address and the information included in the message. This information is used to respond and is kept in the email service until the request is handled and for any period needed to meet legal obligations or protect rights.

## Storage and deletion

Users can delete scripts and folders from the app library. When sync is available, the deletion is sent to the user’s private CloudKit database. Users can also manage iCloud data using Apple’s controls. Deleting the app alone does not delete data already synced to iCloud. If iCloud is unavailable, a local deletion syncs after the connection returns.

The operator does not provide Gazelo accounts or maintain a separate store of user scripts, so the operator cannot sign in to a user’s private library or delete it from the user’s iCloud. Contact the operator at the address above for instructions or questions about data handling.

PiP diagnostics in debug builds may temporarily write the time, app and PiP state, audio session state, and error text to the device. They do not include script content, audio recordings, or recognized speech, and are not sent to the operator. This debug logging is disabled in release builds.

## User rights and security

To the extent provided by applicable law, users may request information about processing, request correction or deletion, and exercise other available rights. Email saveo.info@gmail.com and identify the right you wish to exercise. Do not include Apple Account passwords or other secrets in your message.

Local data is protected by iOS, iPadOS, and macOS security features. Apple provides iCloud sync and storage. Users are responsible for protecting their device and Apple Account. Do not use voice scrolling with confidential text if you do not agree to the possible transfer of audio and context to Apple.

## Changes to this policy

The operator may update this policy when the app, data practices, or legal requirements change. The new version is published on the [Gazelo Privacy Policy page](https://github.com/sasha1234568/sufler-legal/blob/main/privacy-en.md) and is available in the app. The revision date appears at the beginning of the policy.
