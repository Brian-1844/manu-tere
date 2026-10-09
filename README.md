# Manu Tere

A voyaging bird that takes visitors around the islands of French Polynesia. It is in English, with Reo Māʻohi words throughout, and is a sister app to Manu Ora.

**Prototype, version 0.1.** Three islands (Tahiti, Moʻorea, Porapora / Bora Bora), a star-navigation voyage between them, nine activities, a passport and a word list.

## Put it online (GitHub Pages)

1. On GitHub, create a new public repository named `manu-tere`.
2. Use **Add file › Upload files** to upload every file from this folder: `index.html`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png` and `README.md`. Then click **Commit**.
3. Open **Settings › Pages**. Under Source, choose **Deploy from a branch**, then branch `main`, folder `/ (root)`, and click **Save**.
4. After a minute or two the app is live at `https://brian-1844.github.io/manu-tere/`.

There is no service worker yet, so an update shows up after a normal reload.

## What's inside

| Island | Activities |
|---|---|
| Tahiti | Te mātete (Papeete market, words for fruit), Faʻaheʻe (catch a wave at Teahupoʻo), ʻOri Tahiti (tap with the tōʻere) |
| Moʻorea | Te tairoto (lagoon friends, look but don't touch), Painapo (pineapple harvest), Te toʻa (replant coral) |
| Porapora | Hoe vaʻa (outrigger race around Otemanu), Fāfā piti (approach a manta gently), Te mau fetiʻa (stars over Matira) |

- **Voyages:** keep the guide star (or the sun) above the mast. Matariʻi sets toward Porapora and ʻAna-mua rises toward Tahiti. The day crossing to Moʻorea follows the sun.
- **Rewards:** finishing all three activities on an island unlocks an item for the bird: a hei, a pāreu, sunglasses.
- **Saving:** progress is saved on the phone only (localStorage). There are no accounts and nothing is sent anywhere.

## Before a public launch

- Have native speakers check every Reo word, the pronunciation hints and the short phrases. The words are kept together in the `W` list at the top of the script.
- Replace the computer voice with real recordings. It is an approximation and does not pronounce the ʻeta.
- Check the travel information (ferry and flight times) with the operators, and add partner links (for example Tahiti Tourisme) if a partnership happens.
- Show sacred places such as Taputapuātea, which is planned for Raiatea, with the guardians' agreement.
