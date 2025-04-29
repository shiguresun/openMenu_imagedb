# Instructions

## Notes
- USA and PAL are considered complete and should not require updates
- All Homebrew belongs in `HB_input`, yes even commercially discs
- All things that aren't homebrew and aren't retail belong in `EX_input`. This includes things like prototypes, demo discs, propeller arena, etc...


## How to add an image
1. add your image with an appropriate name to the intended folder, image should be square of at least 512x512 or whatever highest resolution is available
    - `Doom (Ian).png` to for Ian Michael's doom port
1. in the `catalogues` folder, in the appropriate csv file add your image name with the Serial used in the IP.BIN of the disc image.
    - If no proper serial exists, e.g. `BOOTDREAMS` then feel free to make up an ID similar to `HB_IAN_DOOM`
    - Created ID's will be honored when making your openMenu gdi from [GDMENUCardManager](https://github.com/mrneo240/GDMENUCardManager/releases/) if you add `serial.txt` with the serial to the disc image folder
    - In this example the new line in `product_hb.csv` would appear as:
    ```
    Doom (Ian).pvr,HB_IAN_DOOM.pvr
    ```
- **Note**: when possible credit authors of the image in the PR you intend to submit

## 以下このリポジトリの特徴
このリポジトリではNTSC-Jに特化したopenmenuのパッケージファイルを製作しています。
現状だと9割位のソフトでパッケージが表示されると思います。

- 以下のソフトは追加していない(プレイすることはできるが、オンラインが必須でかなり遊べる範囲が限られている等):
  - クリスマス シーマン 〜想いを伝えるもうひとつの方法〜
  - ぐるぐる温泉2
  - ぐるぐる温泉3
  - サクラ大戦オンライン
  - JRA PAT for Dreamcast
  - JRA PAT for Dreamcast V50
  - でじこのまいブラ
  - 電波少年的懸賞生活ソフト なすびの部屋
  - ビジュアルパーク
  - マイクロソフト ウェブ・ティービー接続キット
  - マイトラックマン
  - 夢馬券'99 インターネット
- 追加が必要な場合はPull requestに書いておいてください。

- 以下のソフトは対応不可(画像が無い、IDが不明等で製作が困難):
  - 体験版などの非売品ソフト
  - 同人DCソフト
  - ドリキャッチシリーズ
  - 栽培ねっと
  - シーマンえさディスク
  - セガカラ for ドリームキャスト
  - センチメンタルグラフティ2 サードウィンドウ
  - トリコロールクライシス　アートパレット
  - ファーストKISS☆物語
