# Manu Tere

A voyaging bird that takes visitors around the islands of French Polynesia. It is in English, with Reo Māʻohi words throughout, and is a sister app to Manu Ora.

**Prototype, version 0.3.** Three islands (Tahiti, Moʻorea, Porapora / Bora Bora), a star-navigation voyage between them, nine activities, five legends, a faʻaʻapu with four crafts, a passport and a word list.

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
- **Faʻaʻapu (garden):** six plots, with plants ready in a few minutes so a visitor can harvest during a stay. The real moon speeds up growth while it is waxing. The real season does too: Matariʻi i niʻa, the season of abundance from 20 November, gives more fruit, and the fruit in season each month (ʻuru, mango, pineapple, tiare) grows twice as fast. Food can be "tasted" for a tip on where to try it. Shells wash up on the beaches, and a pearl line in the lagoon opens after Porapora.
- **Crafts:** a sun-printed pāreu (cotton and a plant dye), a woven tāupoʻo (pandanus, over-and-under weaving), a hei poe (pearls and shells) and a tapa (beat ʻuru bark with the ʻiʻe, then print motifs). The bird wears what you make, and every craft says where to see the real thing.
- **Te raʻi (the star button at the top):** the night sky of the fenua, as in Manu Ora. Tap a star to learn its Reo name and story, play "find the star", and see tonight's moon with its Tahitian night name. Learning all 11 gives the bird a cloak of stars.
- **Surf:** catch the swell at the right moment, then ride the pocket by pumping, without getting too close to the lip or too far out on the shoulder.
- **ʻĀʻai (legends):** Hina and the eel (Tahiti), Pai and the pierced mountain (Moʻorea), ʻOro and the rainbow (Porapora), and two garden legends: Ruataʻata and the ʻuru, and Hina in the moon. Each legend gives seeds or materials.
- **Saving:** progress is saved on the phone only (localStorage). There are no accounts and nothing is sent anywhere.

## Before a public launch

- Have native speakers check every Reo word, the pronunciation hints and the short phrases. The words are kept together in the `W` list at the top of the script.
- Add recordings by native speakers if you want sound for the words. The computer voice has been removed, so for now the words are written only, with a pronunciation guide.
- Check the travel information (ferry and flight times) with the operators, and add partner links (for example Tahiti Tourisme) if a partnership happens.
- Show sacred places such as Taputapuātea, which is planned for Raiatea, with the guardians' agreement.
- Have the legends checked by a storyteller or the Maison de la Culture. Each legend exists in several versions, and the app says which version it follows.
