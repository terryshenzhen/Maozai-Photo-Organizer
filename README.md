# Maozai Photo Organizer
Download:
https://github.com/terryshenzhen/Maozai-Photo-Organizer/releases/tag/V1.0

or 

https://gitee.com/zzzbbb001_admin/maozai-photo-organizer/releases/tag/v1.0

//--------------English--------------

# Maozai Photo Organizer User Manual

Sorts photos, videos and audio recordings scattered across folders into tidy folders by shooting date, and automatically removes duplicates and empty folders.

**Keywords**: Maozai Photo Organizer, photo organizer, album organizer, sort photos by date, video organizer, photo deduplication, delete duplicate photos, batch photo organizer, organize phone photos, audio file organizer

---

## What problems it solves

- Photos and videos piled up in a mess → automatically sorted by **year/year_month**
- Too many screenshots → moved into a separate **screenshot** folder
- Audio recordings → moved into **audio/year_month** folders
- The same file saved multiple times → duplicates are detected and removed automatically

## How to use (3 steps)

1. **Choose the source folder**: where your photos/videos are
2. **Choose the output folder**: where the sorted result goes
3. Click **Start** and wait for it to finish (you can pause, resume or cancel)

## What the output looks like

```
Output folder/
├── 2020/2020_5/        ← photos and videos taken in May 2020
├── 2021/2021_10/
├── screenshot/2023/    ← screenshots, grouped by year
├── audio/2025_3/       ← audio files, grouped by year and month
└── unknow/             ← files whose date can't be recognized (kept for manual review)
```

## FAQ

**Q: Will it overwrite or lose my files?**
No. Files with the same name are compared by content first: the source is deleted only if the contents are identical; otherwise the file is renamed (with a number suffix).

**Q: What happens if I cancel halfway?**
The sorted part is kept, unprocessed files stay untouched, and empty folders are not cleaned up.

**Q: Some files end up in "unknow" or are not classified. What can I do?**
Rename the file to include a date in its name, and the software will recognize it, e.g.:
- `2023_05_01` (separated by underscores)
- `20230501` (digits together)
If it still can't be recognized, please handle it manually or contact the author.

---
Author contact: 825772667@qq.com

---

## ⚠️ Important Notice (please read first)

This software **moves files, deletes duplicate files and deletes empty folders**. To avoid loss, please:

1. **Back up first**: before the first use, copy your important photos and videos somewhere else.
2. **Try it small first**: test on an unimportant folder, confirm the result is what you expect, then organize everything.
3. **Choose the output location carefully**: pick a dedicated empty folder, not the Desktop or the system drive root.

**Disclaimer**: This software is provided "as is". The author has made every effort to ensure the sorting logic is correct, but accepts no liability for any file loss, damage or accidental deletion caused by using this software. By using it, you acknowledge that you have read and accepted this notice.

//--------------Deutsch--------------

# Maozai Photo Organizer Benutzerhandbuch

Sortiert Fotos, Videos und Audioaufnahmen, die über viele Ordner verstreut sind, nach Aufnahmedatum in übersichtliche Ordner und entfernt automatisch Duplikate und leere Ordner.

**Schlüsselwörter**: Maozai Photo Organizer, Fotos sortieren, Alben organisieren, Fotos nach Datum sortieren, Videos sortieren, doppelte Fotos löschen, Fotos deduplizieren, Handy-Fotos organisieren, Audiodateien sortieren

---

## Welche Probleme es löst

- Fotos und Videos liegen unübersichtlich durcheinander → automatisch nach **Jahr/Jahr_Monat** sortiert
- Zu viele Screenshots → in einen separaten **screenshot**-Ordner verschoben
- Audioaufnahmen → in **audio/Jahr_Monat**-Ordner verschoben
- Dieselbe Datei mehrfach gespeichert → Duplikate werden erkannt und entfernt

## So wird es verwendet (3 Schritte)

1. **Quellordner wählen**: wo sich Ihre Fotos/Videos befinden
2. **Zielordner wählen**: wohin das sortierte Ergebnis kommt
3. Auf **Start** klicken und warten (Pausieren, Fortsetzen oder Abbrechen jederzeit möglich)

## So sieht das Ergebnis aus

```
Zielordner/
├── 2020/2020_5/        ← Fotos und Videos aus Mai 2020
├── 2021/2021_10/
├── screenshot/2023/    ← Screenshots, nach Jahr gruppiert
├── audio/2025_3/       ← Audiodateien, nach Jahr und Monat gruppiert
└── unknow/             ← Dateien ohne erkennbares Datum (bleiben zur manuellen Prüfung erhalten)
```

## Häufige Fragen

**F: Werden meine Dateien überschrieben oder gehen verloren?**
Nein. Dateien mit gleichem Namen werden zuerst inhaltlich verglichen: Nur bei identischem Inhalt wird die Quelle gelöscht; andernfalls wird die Datei umbenannt (mit Nummernsuffix).

**F: Was passiert, wenn ich abbreche?**
Der bereits sortierte Teil bleibt erhalten, unbearbeitete Dateien bleiben unverändert, und leere Ordner werden nicht gelöscht.

**F: Manche Dateien landen in „unknow". Was kann ich tun?**
Benennen Sie die Datei so um, dass ihr Name ein Datum enthält, z. B.:
- `2023_05_01` (mit Unterstrichen)
- `20230501` (Ziffern aneinander)
Wenn es weiterhin nicht erkannt wird, bearbeiten Sie die Datei bitte manuell oder kontaktieren Sie den Autor.

---
Kontakt zum Autor: 825772667@qq.com

---

## ⚠️ Wichtiger Hinweis (bitte zuerst lesen)

Diese Software **verschiebt Dateien, löscht Duplikate und löscht leere Ordner**. Um Verluste zu vermeiden:

1. **Zuerst sichern**: Kopieren Sie wichtige Fotos und Videos vor der ersten Verwendung an einen anderen Ort.
2. **Zuerst klein testen**: Testen Sie mit einem unwichtigen Ordner und prüfen Sie das Ergebnis, bevor Sie alles sortieren.
3. **Zielort sorgfältig wählen**: Verwenden Sie einen eigenen leeren Ordner, nicht den Desktop oder das Stammverzeichnis des Systemlaufwerks.

**Haftungsausschluss**: Diese Software wird „wie besehen" bereitgestellt. Der Autor hat sich bemüht, die Sortierlogik korrekt zu gestalten, übernimmt jedoch keine Haftung für Dateiverluste, Beschädigungen oder versehentliches Löschen. Mit der Nutzung erkennen Sie diesen Hinweis an.

#### 介绍
**关键词**：猫仔相册整理、照片整理、相册整理、照片按日期分类、视频整理、图片去重、重复照片删除、批量整理照片、手机照片导出整理、录音文件整理

# 猫仔相册整理 使用说明

把散落在各个文件夹里的照片、视频、录音，按拍摄日期自动归类到整齐的文件夹中，并自动清理重复文件和空文件夹。

**关键词**：猫仔相册整理、照片整理、相册整理、照片按日期分类、视频整理、图片去重、重复照片删除、批量整理照片、手机照片导出整理、录音文件整理

---

## 它能帮你解决手机/相机图片凌乱问题

- 照片视频堆在一起，杂乱无章 → 按 **年/年_月** 自动分好
- 截图太多 → 归入单独的 **screenshot** 文件夹
- 录音文件 → 归入 **audio/年_月** 文件夹
- 同一个文件存了多份 → 自动识别重复，删掉重复文件

## 怎么用（三步）

1. **选择源文件夹**：  你要整理的照片/视频所在的文件夹
2. **选择输出文件夹**：整理结果放到哪里
3. 点击 **开始**，     等待完成即可 

## 整理后的目录长什么样

```
输出文件夹/
├── 2020/2020_5/        ← 2020年5月拍摄的照片和视频
├── 2021/2021_10/
├── screenshot/2023/    ← 截图，按年份归类
├── audio/2025_3/       ← 录音等音频文件，按年月归类
└── unknow/             ← 认不出日期的文件（不会丢，等你人工处理）
```

## 常见问题

**问：会不会覆盖或弄丢我的文件？**
不会。同名文件会先比对内容：内容完全相同才删除源文件；内容不同会自动改名（加序号）。

**问：整理一半取消了会怎样？**
已整理的部分保留，未处理的文件原样不动，也不会清理空文件夹。

**问：有的文件认不出日期，进了 unknow 文件夹或者未归类，怎么办？**
可以手动给文件改名，在文件名里加上日期，软件就能认出来了，例如：
- `2023_05_01`（用下划线分隔）
- `20230501`（年月日连在一起）
实在无法识别的，请手动处理或反馈给作者。

---
作者联系方式：825772667@qq.com

---

## ⚠️ 重要提醒（请务必先读）

本软件会 **移动文件、删除重复文件、删除空文件夹**。为避免损失，请注意：

1. **先备份**：第一次使用前，请先把重要照片视频复制一份到别处。
2. **先小范围试用**：先用一个不太重要的文件夹试整理，确认结果符合预期后，再整理全部文件。
3. **确认输出位置**：输出文件夹请选一个专门的空文件夹，不要选桌面、系统盘根目录等重要位置。

**免责声明**：本软件按"现状"提供。作者已尽力保证整理逻辑正确，但因使用本软件造成的任何文件丢失、损坏或误删，作者不承担任何责任。使用本软件即表示你已阅读并接受以上提醒。

//--------------日本語--------------

# Maozai Photo Organizer ユーザーマニュアル

フォルダに散らかった写真・動画・録音を撮影日順にきれいなフォルダへ自動で整理し、重複ファイルと空フォルダも自動で削除します。

**キーワード**：Maozai Photo Organizer、写真整理、アルバム整理、日付順写真分類、動画整理、重複写真削除、写真一括整理、スマホ写真整理、音声ファイル整理

---

## 解決できる問題

- 写真や動画が散らかっている → **年/年_月** で自動分類
- スクリーンショットが多すぎる → **screenshot** フォルダへ分類
- 録音ファイル → **audio/年_月** フォルダへ分類
- 同じファイルが複数ある → 重複を自動検出して削除

## 使い方（3ステップ）

1. **ソースフォルダを選択**：整理したい写真・動画があるフォルダ
2. **出力フォルダを選択**：整理結果の保存先
3. **開始** をクリックして完了を待つ（一時停止・再開・キャンセル可）

## 整理後のフォルダ構成

```
出力フォルダ/
├── 2020/2020_5/        ← 2020年5月に撮影した写真と動画
├── 2021/2021_10/
├── screenshot/2023/    ← スクリーンショット（年ごと）
├── audio/2025_3/       ← 音声ファイル（年月ごと）
└── unknow/             ← 日付を認識できないファイル（手動確認用に保持）
```

## よくある質問

**Q：ファイルが上書きされたり失われたりしませんか？**
しません。同名ファイルは内容を比較し、完全に同じ場合のみ元ファイルを削除します。異なる場合は番号付きで自動リネームされます。

**Q：途中でキャンセルするとどうなりますか？**
整理済みの部分はそのまま残り、未処理のファイルは変更されず、空フォルダの削除も行われません。

**Q：「unknow」に入ったファイルはどうすれば？**
ファイル名に日付を含めるように改名すれば認識されます。例：
- `2023_05_01`（アンダースコア区切り）
- `20230501`（数字のみ連続）
それでも認識されない場合は手動で処理するか、作者にご連絡ください。

---
作者連絡先：825772667@qq.com

---

## ⚠️ 重要な注意（必ずお読みください）

本ソフトは **ファイルの移動、重複ファイルの削除、空フォルダの削除** を行います。損失を防ぐため：

1. **まずバックアップ**：初回使用前に、大切な写真・動画を別の場所へコピーしてください。
2. **まず小規模で試す**：重要でないフォルダで試し、結果に納得してから全体を整理してください。
3. **出力先の確認**：専用の空フォルダを選び、デスクトップやシステムドライブ直下は避けてください。

**免責事項**：本ソフトは「現状のまま」提供されます。作者は整理ロジックの正確性に努めていますが、使用によるファイルの紛失・破損・誤削除について一切の責任を負いません。使用をもって本注意に同意したものとみなします。

//--------------Français--------------

# Maozai Photo Organizer — Manuel d'utilisation

Trie automatiquement les photos, vidéos et enregistrements audio dispersés dans vos dossiers par date de prise de vue, et supprime les doublons ainsi que les dossiers vides.

**Mots-clés** : Maozai Photo Organizer, trier photos, organiser albums, trier photos par date, trier vidéos, supprimer photos en double, déduplication photos, organiser photos de téléphone, trier fichiers audio

---

## Les problèmes qu'il résout

- Photos et vidéos en désordre → tri automatique par **année/année_mois**
- Trop de captures d'écran → dossier **screenshot** séparé
- Enregistrements audio → dossiers **audio/année_mois**
- Même fichier en plusieurs exemplaires → doublons détectés et supprimés

## Mode d'emploi (3 étapes)

1. **Choisir le dossier source** : où se trouvent vos photos/vidéos
2. **Choisir le dossier de sortie** : où placer le résultat trié
3. Cliquer sur **Démarrer** et attendre la fin (pause, reprise ou annulation possibles)

## Structure du résultat

```
Dossier de sortie/
├── 2020/2020_5/        ← photos et vidéos de mai 2020
├── 2021/2021_10/
├── screenshot/2023/    ← captures d'écran, par année
├── audio/2025_3/       ← fichiers audio, par année et mois
└── unknow/             ← fichiers sans date reconnue (conservés pour tri manuel)
```

## Questions fréquentes

**Q : Mes fichiers risquent-ils d'être écrasés ou perdus ?**
Non. Les fichiers portant le même nom sont d'abord comparés par leur contenu : la source n'est supprimée que si le contenu est identique ; sinon le fichier est renommé (avec un suffixe numérique).

**Q : Que se passe-t-il si j'annule en cours de route ?**
La partie déjà triée est conservée, les fichiers non traités restent intacts, et les dossiers vides ne sont pas supprimés.

**Q : Certains fichiers aboutissent dans « unknow ». Que faire ?**
Renommez le fichier en ajoutant une date dans son nom, par exemple :
- `2023_05_01` (avec des traits de soulignement)
- `20230501` (chiffres accolés)
Si la date n'est toujours pas reconnue, traitez le fichier manuellement ou contactez l'auteur.

---
Contact de l'auteur : 825772667@qq.com

---

## ⚠️ Avertissement important (à lire d'abord)

Ce logiciel **déplace des fichiers, supprime les doublons et supprime les dossiers vides**. Pour éviter toute perte :

1. **Sauvegardez d'abord** : avant la première utilisation, copiez vos photos et vidéos importantes ailleurs.
2. **Testez d'abord sur un petit dossier** : vérifiez le résultat avant de tout trier.
3. **Choisissez bien le dossier de sortie** : utilisez un dossier vide dédié, pas le Bureau ni la racine du disque système.

**Clause de non-responsabilité** : Ce logiciel est fourni « en l'état ». L'auteur a tout fait pour garantir l'exactitude du tri, mais décline toute responsabilité en cas de perte, d'endommagement ou de suppression accidentelle de fichiers. L'utilisation du logiciel vaut acceptation de cet avertissement.

//--------------한국어--------------

# Maozai Photo Organizer 사용 설명서

여러 폴더에 흩어진 사진, 동영상, 녹음 파일을 촬영 날짜별로 깔끔하게 자동 분류하고, 중복 파일과 빈 폴더를 자동으로 정리합니다.

**키워드**: Maozai Photo Organizer, 사진 정리, 앨범 정리, 날짜별 사진 분류, 동영상 정리, 중복 사진 삭제, 사진 일괄 정리, 휴대폰 사진 정리, 음성 파일 정리

---

## 해결해 주는 문제

- 사진과 동영상이 뒤섞여 있음 → **연도/연도_월** 로 자동 분류
- 스크린샷이 너무 많음 → 별도 **screenshot** 폴더로 분류
- 녹음 파일 → **audio/연도_월** 폴더로 분류
- 같은 파일이 여러 개 → 중복을 자동으로 찾아 삭제

## 사용 방법 (3단계)

1. **소스 폴더 선택**: 정리할 사진/동영상이 있는 폴더
2. **출력 폴더 선택**: 정리 결과를 저장할 위치
3. **시작** 클릭 후 완료 대기 (일시 중지/재개/취소 가능)

## 정리 후 폴더 모습

```
출력 폴더/
├── 2020/2020_5/        ← 2020년 5월 촬영 사진·동영상
├── 2021/2021_10/
├── screenshot/2023/    ← 스크린샷 (연도별)
├── audio/2025_3/       ← 음성 파일 (연월별)
└── unknow/             ← 날짜를 인식하지 못한 파일 (수동 확인용 보관)
```

## 자주 묻는 질문

**Q: 파일이 덮어씌워지거나 사라지지 않나요?**
아니요. 같은 이름의 파일은 먼저 내용을 비교합니다. 내용이 완전히 같을 때만 원본을 삭제하고, 다르면 번호를 붙여 자동으로 이름을 바꿉니다.

**Q: 중간에 취소하면 어떻게 되나요?**
이미 정리된 부분은 그대로 유지되고, 처리되지 않은 파일은 변경되지 않으며, 빈 폴더도 삭제되지 않습니다.

**Q: 날짜를 인식하지 못해 "unknow"에 들어간 파일은 어떻게 하나요?**
파일 이름에 날짜를 넣어 이름을 바꾸면 인식됩니다. 예:
- `2023_05_01` (밑줄로 구분)
- `20230501` (숫자 연속)
그래도 인식되지 않으면 수동으로 처리하거나 개발자에게 문의하세요.

---
개발자 연락처: 825772667@qq.com

---

## ⚠️ 중요 안내 (먼저 읽어 주세요)

이 소프트웨어는 **파일 이동, 중복 파일 삭제, 빈 폴더 삭제** 를 수행합니다. 손실 방지를 위해:

1. **먼저 백업**: 처음 사용하기 전에 중요한 사진과 동영상을 다른 곳에 복사하세요.
2. **먼저 작은 범위로 테스트**: 중요하지 않은 폴더로 먼저 시험해 보고 결과를 확인한 후 전체를 정리하세요.
3. **출력 위치 확인**: 전용 빈 폴더를 선택하고, 바탕 화면이나 시스템 드라이브 루트는 피하세요.

**면책 조항**: 이 소프트웨어는 "있는 그대로" 제공됩니다. 개발자는 정리 로직의 정확성을 위해 노력했지만, 사용으로 인한 파일 손실·손상·오삭제에 대해 책임지지 않습니다. 사용 시 본 안내를 읽고 동의한 것으로 간주됩니다.

//--------------Nederlands--------------

# Maozai Photo Organizer Gebruikershandleiding

Sorteert foto's, video's en audio-opnames die verspreid over mappen staan automatisch op opnamedatum in nette mappen, en verwijdert dubbele bestanden en lege mappen.

**Trefwoorden**: Maozai Photo Organizer, foto's sorteren, albums organiseren, foto's op datum sorteren, video's organiseren, dubbele foto's verwijderen, telefoonfoto's organiseren, audiobestanden sorteren

---

## Welke problemen het oplost

- Foto's en video's liggen rommelig door elkaar → automatisch gesorteerd op **jaar/jaar_maand**
- Te veel schermafbeeldingen → aparte **screenshot**-map
- Audio-opnames → **audio/jaar_maand**-mappen
- Hetzelfde bestand meerdere keren opgeslagen → duplicaten worden gedetecteerd en verwijderd

## Gebruik (3 stappen)

1. **Kies de bronmap**: waar uw foto's/video's staan
2. **Kies de uitvoermap**: waar het gesorteerde resultaat heen gaat
3. Klik op **Start** en wacht tot het klaar is (pauzeren, hervatten of annuleren kan)

## Zo ziet het resultaat eruit

```
Uitvoermap/
├── 2020/2020_5/        ← foto's en video's van mei 2020
├── 2021/2021_10/
├── screenshot/2023/    ← schermafbeeldingen, per jaar
├── audio/2025_3/       ← audiobestanden, per jaar en maand
└── unknow/             ← bestanden zonder herkenbare datum (bewaard voor handmatige controle)
```

## Veelgestelde vragen

**V: Worden mijn bestanden overschreven of raken ze kwijt?**
Nee. Bestanden met dezelfde naam worden eerst op inhoud vergeleken: alleen bij identieke inhoud wordt het bronbestand verwijderd; anders wordt het bestand hernoemd (met een nummer).

**V: Wat gebeurt er als ik halverwege annuleer?**
Het gesorteerde deel blijft behouden, onverwerkte bestanden blijven onaangetast, en lege mappen worden niet verwijderd.

**V: Sommige bestanden belanden in "unknow". Wat kan ik doen?**
Hernoem het bestand zodat de naam een datum bevat, bijvoorbeeld:
- `2023_05_01` (met underscores)
- `20230501` (cijfers aan elkaar)
Wordt het nog steeds niet herkend, verwerk het bestand dan handmatig of neem contact op met de auteur.

---
Contact auteur: 825772667@qq.com

---

## ⚠️ Belangrijke melding (lees dit eerst)

Deze software **verplaatst bestanden, verwijdert duplicaten en verwijdert lege mappen**. Om verlies te voorkomen:

1. **Maak eerst een back-up**: kopieer belangrijke foto's en video's vóór het eerste gebruik naar een andere locatie.
2. **Test eerst klein**: test met een onbelangrijke map en controleer het resultaat voordat u alles sorteert.
3. **Kies de uitvoerlocatie zorgvuldig**: gebruik een eigen lege map, niet het Bureaublad of de hoofdmap van de systeemschijf.

**Vrijwaring**: Deze software wordt geleverd "zoals deze is". De auteur heeft zijn best gedaan de sorteerlogica correct te maken, maar aanvaardt geen aansprakelijkheid voor verlies, beschadiging of onbedoelde verwijdering van bestanden. Door gebruik aanvaardt u deze melding.

//--------------Svenska--------------

# Maozai Photo Organizer Användarmanual

Sorterar foton, videor och ljudinspelningar som ligger utspridda i mappar efter fotograferingsdatum till snygga mappar, och tar automatiskt bort dubbletter och tomma mappar.

**Nyckelord**: Maozai Photo Organizer, sortera foton, organisera album, sortera foton efter datum, sortera videor, ta bort dubbla foton, organisera mobilfoton, sortera ljudfiler

---

## Problem som löses

- Foton och videor i oordning → sorteras automatiskt efter **år/år_månad**
- För många skärmdumpar → flyttas till en egen **screenshot**-mapp
- Ljudinspelningar → flyttas till **audio/år_månad**-mappar
- Samma fil sparad flera gånger → dubbletter upptäcks och tas bort

## Så använder du det (3 steg)

1. **Välj källmapp**: där dina foton/videor finns
2. **Välj utdatamapp**: dit det sorterade resultatet ska
3. Klicka på **Start** och vänta tills det är klart (paus, återuppta eller avbryt går)

## Så ser resultatet ut

```
Utdatamapp/
├── 2020/2020_5/        ← foton och videor från maj 2020
├── 2021/2021_10/
├── screenshot/2023/    ← skärmdumpar, per år
├── audio/2025_3/       ← ljudfiler, per år och månad
└── unknow/             ← filer utan igenkännbart datum (sparas för manuell granskning)
```

## Vanliga frågor

**F: Kan mina filer skrivas över eller försvinna?**
Nej. Filer med samma namn jämförs först innehållsmässigt: källan raderas bara om innehållet är identiskt; annars döps filen om (med ett nummersuffix).

**F: Vad händer om jag avbryter halvvägs?**
Den sorterade delen behålls, obehandlade filer förblir orörda, och tomma mappar tas inte bort.

**F: Vissa filer hamnar i "unknow". Vad kan jag göra?**
Döp om filen så att namnet innehåller ett datum, t.ex.:
- `2023_05_01` (med understreck)
- `20230501` (siffror i följd)
Om det fortfarande inte känns igen, hantera filen manuellt eller kontakta utvecklaren.

---
Kontakt: 825772667@qq.com

---

## ⚠️ Viktig information (läs först)

Programvaran **flyttar filer, raderar dubbletter och raderar tomma mappar**. För att undvika förluster:

1. **Säkerhetskopiera först**: kopiera viktiga foton och videor till en annan plats före första användningen.
2. **Testa litet först**: prova med en oviktig mapp och kontrollera resultatet innan du sorterar allt.
3. **Välj utdataplats noggrant**: använd en egen tom mapp, inte Skrivbordet eller systemdiskens rot.

**Ansvarsfriskrivning**: Programvaran tillhandahålls "i befintligt skick". Utvecklaren har gjort sitt bästa för att sorteringslogiken ska vara korrekt, men tar inget ansvar för förlorade, skadade eller oavsiktligt raderade filer. Genom att använda programvaran godkänner du detta.

//--------------Norsk--------------

# Maozai Photo Organizer Brukerhåndbok

Sorterer bilder, videoer og lydopptak som ligger spredt i mapper etter dato, og fjerner automatisk duplikater og tomme mapper.

**Nøkkelord**: Maozai Photo Organizer, sortere bilder, organisere album, sortere bilder etter dato, sortere videoer, slette duplikate bilder, organisere mobilbilder, sortere lydfiler

---

## Problemer det løser

- Bilder og videoer i uorden → sorteres automatisk etter **år/år_måned**
- For mange skjermbilder → flyttes til en egen **screenshot**-mappe
- Lydopptak → flyttes til **audio/år_måned**-mapper
- Samme fil lagret flere ganger → duplikater oppdages og fjernes

## Slik bruker du det (3 trinn)

1. **Velg kildemappe**: der bildene/videoene dine ligger
2. **Velg målmappe**: dit det sorterte resultatet skal
3. Klikk **Start** og vent til det er ferdig (pause, fortsett eller avbryt når som helst)

## Slik ser resultatet ut

```
Målmappe/
├── 2020/2020_5/        ← bilder og videoer fra mai 2020
├── 2021/2021_10/
├── screenshot/2023/    ← skjermbilder, per år
├── audio/2025_3/       ← lydfiler, per år og måned
└── unknow/             ← filer uten gjenkjennelig dato (beholdes til manuell gjennomgang)
```

## Vanlige spørsmål

**S: Kan filene mine bli overskrevet eller gå tapt?**
Nei. Filer med samme navn sammenlignes først etter innhold: kilden slettes bare hvis innholdet er identisk; ellers får filen et nytt navn (med nummersuffiks).

**S: Hva skjer hvis jeg avbryter underveis?**
Den sorterte delen beholdes, ubehandlede filer forblir urørte, og tomme mapper slettes ikke.

**S: Noen filer havner i «unknow». Hva kan jeg gjøre?**
Gi filen et nytt navn som inneholder en dato, f.eks.:
- `2023_05_01` (med understreker)
- `20230501` (sifre sammen)
Hvis den fortsatt ikke gjenkjennes, håndter filen manuelt eller kontakt utvikleren.

---
Kontakt: 825772667@qq.com

---

## ⚠️ Viktig merknad (les dette først)

Denne programvaren **flytter filer, sletter duplikater og sletter tomme mapper**. For å unngå tap:

1. **Ta sikkerhetskopi først**: kopier viktige bilder og videoer til et annet sted før første bruk.
2. **Test lite først**: prøv med en uviktig mappe og sjekk resultatet før du sorterer alt.
3. **Velg målplassering med omhu**: bruk en egen tom mappe, ikke Skrivebordet eller roten på systemdisken.

**Ansvarsfraskrivelse**: Programvaren leveres «som den er». Utvikleren har gjort sitt beste for at sorteringslogikken skal være riktig, men påtar seg intet ansvar for tapte, skadede eller utilsiktet slettede filer. Ved bruk aksepterer du denne merknaden.

//--------------Dansk--------------

# Maozai Photo Organizer Brugervejledning

Sorterer fotos, videoer og lydoptagelser, der ligger spredt i mapper, efter optagedato i pæne mapper og fjerner automatisk dubletter og tomme mapper.

**Nøgleord**: Maozai Photo Organizer, sorter fotos, organisér album, sorter fotos efter dato, sorter videoer, slet dublerede fotos, organisér mobilfotos, sorter lydfiler

---

## Problemer det løser

- Fotos og videoer i rodet → sorteres automatisk efter **år/år_måned**
- For mange skærmbilleder → flyttes til en separat **screenshot**-mappe
- Lydoptagelser → flyttes til **audio/år_måned**-mapper
- Samme fil gemt flere gange → dubletter findes og fjernes

## Sådan bruger du det (3 trin)

1. **Vælg kildemappe**: hvor dine fotos/videoer ligger
2. **Vælg destinationsmappe**: hvor det sorterede resultat skal hen
3. Klik på **Start** og vent, til det er færdigt (pause, genoptag eller annullér undervejs)

## Sådan ser resultatet ud

```
Destinationsmappe/
├── 2020/2020_5/        ← fotos og videoer fra maj 2020
├── 2021/2021_10/
├── screenshot/2023/    ← skærmbilleder, pr. år
├── audio/2025_3/       ← lydfiler, pr. år og måned
└── unknow/             ← filer uden genkendelig dato (bevares til manuel gennemgang)
```

## Ofte stillede spørgsmål

**S: Kan mine filer blive overskrevet eller gå tabt?**
Nej. Filer med samme navn sammenlignes først efter indhold: kilden slettes kun, hvis indholdet er identisk; ellers omdøbes filen (med nummersuffiks).

**S: Hvad sker der, hvis jeg annullerer halvvejs?**
Den sorterede del beholdes, ubehandlede filer forbliver urørte, og tomme mapper slettes ikke.

**S: Nogle filer ender i "unknow". Hvad kan jeg gøre?**
Omdøb filen, så navnet indeholder en dato, f.eks.:
- `2023_05_01` (med understregninger)
- `20230501` (cifre i træk)
Hvis den stadig ikke genkendes, så håndtér filen manuelt eller kontakt forfatteren.

---
Kontakt: 825772667@qq.com

---

## ⚠️ Vigtig meddelelse (læs dette først)

Denne software **flytter filer, sletter dubletter og sletter tomme mapper**. For at undgå tab:

1. **Sikkerhedskopiér først**: kopiér vigtige fotos og videoer et andet sted hen før første brug.
2. **Test i lille skala først**: prøv med en uvigtig mappe og tjek resultatet, før du sorterer alt.
3. **Vælg destinationsplacering omhyggeligt**: brug en dedikeret tom mappe, ikke Skrivebordet eller systemdrevets rod.

**Ansvarsfraskrivelse**: Denne software leveres "som den er". Forfatteren har gjort sit bedste for at sikre korrekt sorteringslogik, men påtager sig intet ansvar for tabte, beskadigede eller utilsigtet slettede filer. Ved at bruge softwaren accepterer du denne meddelelse.

//--------------Italiano--------------

# Maozai Photo Organizer Manuale utente

Ordina foto, video e registrazioni audio sparsi in varie cartelle in base alla data di scatto, eliminando automaticamente duplicati e cartelle vuote.

**Parole chiave**: Maozai Photo Organizer, organizzare foto, organizzare album, ordinare foto per data, organizzare video, eliminare foto duplicate, organizzare foto del telefono, organizzare file audio

---

## Problemi che risolve

- Foto e video in disordine → ordinati automaticamente per **anno/anno_mese**
- Troppe schermate → spostate in una cartella **screenshot** dedicata
- Registrazioni audio → spostate in cartelle **audio/anno_mese**
- Lo stesso file salvato più volte → i duplicati vengono rilevati ed eliminati

## Come si usa (3 passaggi)

1. **Scegli la cartella di origine**: dove si trovano foto/video
2. **Scegli la cartella di destinazione**: dove mettere il risultato
3. Clicca **Avvia** e attendi il completamento (pausa, ripresa o annullamento possibili)

## Struttura del risultato

```
Cartella di destinazione/
├── 2020/2020_5/        ← foto e video di maggio 2020
├── 2021/2021_10/
├── screenshot/2023/    ← schermate, per anno
├── audio/2025_3/       ← file audio, per anno e mese
└── unknow/             ← file senza data riconoscibile (conservati per controllo manuale)
```

## Domande frequenti

**D: I miei file rischiano di essere sovrascritti o persi?**
No. I file con lo stesso nome vengono prima confrontati nel contenuto: l'originale viene eliminato solo se il contenuto è identico; altrimenti il file viene rinominato (con un suffisso numerico).

**D: Cosa succede se annullo a metà?**
La parte già ordinata viene mantenuta, i file non elaborati restano intatti e le cartelle vuote non vengono eliminate.

**D: Alcuni file finiscono in "unknow". Cosa posso fare?**
Rinomina il file includendo una data nel nome, ad esempio:
- `2023_05_01` (con trattini bassi)
- `20230501` (cifre consecutive)
Se non viene ancora riconosciuto, gestiscilo manualmente o contatta l'autore.

---
Contatto dell'autore: 825772667@qq.com

---

## ⚠️ Avviso importante (leggere prima)

Questo software **sposta file, elimina duplicati ed elimina cartelle vuote**. Per evitare perdite:

1. **Fai prima un backup**: prima del primo utilizzo, copia foto e video importanti altrove.
2. **Prova prima su piccola scala**: testa con una cartella non importante e verifica il risultato prima di ordinare tutto.
3. **Scegli con cura la destinazione**: usa una cartella vuota dedicata, non il Desktop né la radice del disco di sistema.

**Esclusione di responsabilità**: Questo software è fornito "così com'è". L'autore ha fatto il possibile per garantire la correttezza dell'ordinamento, ma declina ogni responsabilità per perdite, danni o eliminazioni accidentali di file. Utilizzando il software accetti questo avviso.

//--------------Español--------------

# Maozai Photo Organizer Manual de usuario

Ordena fotos, videos y grabaciones de audio dispersos en carpetas según su fecha, y elimina automáticamente duplicados y carpetas vacías.

**Palabras clave**: Maozai Photo Organizer, organizar fotos, organizar álbumes, ordenar fotos por fecha, organizar videos, eliminar fotos duplicadas, organizar fotos del móvil, organizar archivos de audio

---

## Qué problemas resuelve

- Fotos y videos desordenados → ordenados automáticamente por **año/año_mes**
- Demasiadas capturas de pantalla → carpeta **screenshot** separada
- Grabaciones de audio → carpetas **audio/año_mes**
- El mismo archivo guardado varias veces → los duplicados se detectan y eliminan

## Cómo usarlo (3 pasos)

1. **Elige la carpeta de origen**: donde están tus fotos/videos
2. **Elige la carpeta de salida**: dónde colocar el resultado
3. Haz clic en **Iniciar** y espera a que termine (puedes pausar, reanudar o cancelar)

## Cómo queda el resultado

```
Carpeta de salida/
├── 2020/2020_5/        ← fotos y videos de mayo de 2020
├── 2021/2021_10/
├── screenshot/2023/    ← capturas de pantalla, por año
├── audio/2025_3/       ← archivos de audio, por año y mes
└── unknow/             ← archivos sin fecha reconocible (se conservan para revisión manual)
```

## Preguntas frecuentes

**P: ¿Puede sobrescribir o perder mis archivos?**
No. Los archivos con el mismo nombre se comparan primero por contenido: el origen solo se elimina si el contenido es idéntico; si no, el archivo se renombra (con un sufijo numérico).

**P: ¿Qué pasa si cancelo a mitad?**
La parte ya ordenada se conserva, los archivos sin procesar quedan intactos y las carpetas vacías no se eliminan.

**P: Algunos archivos acaban en "unknow". ¿Qué puedo hacer?**
Renombra el archivo incluyendo una fecha en el nombre, por ejemplo:
- `2023_05_01` (con guiones bajos)
- `20230501` (dígitos seguidos)
Si aún así no se reconoce, trátalo manualmente o contacta con el autor.

---
Contacto del autor: 825772667@qq.com

---

## ⚠️ Aviso importante (léelo primero)

Este software **mueve archivos, elimina duplicados y elimina carpetas vacías**. Para evitar pérdidas:

1. **Haz primero una copia de seguridad**: antes del primer uso, copia tus fotos y videos importantes a otro lugar.
2. **Prueba primero en pequeño**: prueba con una carpeta sin importancia y confirma el resultado antes de organizarlo todo.
3. **Elige bien la ubicación de salida**: usa una carpeta vacía dedicada, no el Escritorio ni la raíz del disco del sistema.

**Descargo de responsabilidad**: Este software se ofrece "tal cual". El autor ha hecho todo lo posible para que la lógica de ordenación sea correcta, pero no asume responsabilidad alguna por pérdidas, daños o eliminaciones accidentales de archivos. Al usar el software aceptas este aviso.

//--------------עברית--------------

# Maozai Photo Organizer מדריך למשתמש

ממיין תמונות, סרטונים והקלטות אודיו הפזורים בתיקיות לתיקיות מסודרות לפי תאריך הצילום, ומוחק אוטומטית כפילויות ותיקיות ריקות.

**מילות מפתח**: Maozai Photo Organizer, מיון תמונות, ארגון אלבומים, מיון תמונות לפי תאריך, מיון סרטונים, מחיקת תמונות כפולות, ארגון תמונות מהטלפון, מיון קבצי אודיו

---

## אילו בעיות הוא פותר

- תמונות וסרטונים מפוזרים בבלגן → ממוינים אוטומטית לפי **שנה/שנה_חודש**
- יותר מדי צילומי מסך → מועברים לתיקיית **screenshot** נפרדת
- הקלטות אודיו → מועברות לתיקיות **audio/שנה_חודש**
- אותו קובץ נשמר כמה פעמים → כפילויות מזוהות ונמחקות

## אופן השימוש (3 שלבים)

1. **בחר תיקיית מקור**: היכן שנמצאות התמונות/הסרטונים
2. **בחר תיקיית יעד**: לאן יועבר התוצאה הממוינת
3. לחץ **התחל** והמתן לסיום (אפשר להשהות, להמשיך או לבטל)

## כך נראית התוצאה

```
תיקיית יעד/
├── 2020/2020_5/        ← תמונות וסרטונים ממאי 2020
├── 2021/2021_10/
├── screenshot/2023/    ← צילומי מסך, לפי שנה
├── audio/2025_3/       ← קבצי אודיו, לפי שנה וחודש
└── unknow/             ← קבצים ללא תאריך מזוהה (נשמרים לטיפול ידני)
```

## שאלות נפוצות

**ש: האם הקבצים שלי עלולים להימחק או להדרס?**
לא. קבצים באותו שם מושווים קודם לפי תוכן: המקור נמחק רק אם התוכן זהה; אחרת הקובץ מקבל שם חדש (עם סיומת מספרית).

**ש: מה קורה אם מבטלים באמצע?**
החלק שכבר סודר נשמר, קבצים שלא עובדו נשארים כפי שהם, ותיקיות ריקות לא נמחקות.

**ש: חלק מהקבצים מגיעים ל-"unknow". מה אפשר לעשות?**
שנה את שם הקובץ כך שיכלול תאריך, למשל:
- `2023_05_01` (עם קווים תחתונים)
- `20230501` (ספרות רצופות)
אם עדיין לא מזוהה, טפל בו ידנית או פנה למחבר.

---
יצירת קשר עם המחבר: 825772667@qq.com

---

## ⚠️ הודעה חשובה (קרא קודם)

תוכנה זו **מעבירה קבצים, מוחקת כפילויות ומוחקת תיקיות ריקות**. כדי למנוע אובדן:

1. **גבה קודם**: לפני השימוש הראשון, העתק תמונות וסרטונים חשובים למקום אחר.
2. **נסה קודם בקנה מידה קטן**: נסה על תיקייה לא חשובה ובדוק את התוצאה לפני מיון הכול.
3. **בחר מיקום יעד בזהירות**: בחר תיקייה ריקה ייעודית, לא את שולחן העבודה או שורש כונן המערכת.

**כתב ויתור**: התוכנה מסופקת "כפי שהיא". המחבר עשה כמיטב יכולתו לדיוק המיון, אך אינו אחראי לאובדן, נזק או מחיקה בשוגג של קבצים. השימוש בתוכנה מהווה הסכמה להודעה זו.

//--------------Suomi--------------

# Maozai Photo Organizer Käyttöohje

Järjestää kansioihin hajallaan olevat valokuvat, videot ja äänitykset kuvauspäivän mukaan siisteihin kansioihin ja poistaa automaattisesti kaksoiskappaleet ja tyhjät kansiot.

**Avainsanat**: Maozai Photo Organizer, valokuvien järjestäminen, albumien järjestäminen, valokuvien lajittelu päivämäärän mukaan, videoiden järjestäminen, päällekkäisten valokuvien poisto, puhelimen valokuvien järjestäminen, äänitiedostojen järjestäminen

---

## Mitä ongelmia se ratkaisee

- Valokuvat ja videot sotkussa → lajitellaan automaattisesti **vuosi/vuosi_kuukausi** -kansioihin
- Liikaa kuvakaappauksia → siirretään erilliseen **screenshot**-kansioon
- Äänitykset → siirretään **audio/vuosi_kuukausi** -kansioihin
- Sama tiedosto tallennettuna monta kertaa → kaksoiskappaleet tunnistetaan ja poistetaan

## Käyttö (3 vaihetta)

1. **Valitse lähdekansio**: missä valokuvat/videot ovat
2. **Valitse kohdekansio**: mihin lajiteltu tulos tulee
3. Napsauta **Käynnistä** ja odota valmistumista (tauko, jatka tai peruuta onnistuu)

## Miltä tulos näyttää

```
Kohdekansio/
├── 2020/2020_5/        ← toukokuussa 2020 otetut valokuvat ja videot
├── 2021/2021_10/
├── screenshot/2023/    ← kuvakaappaukset vuosittain
├── audio/2025_3/       ← äänitiedostot vuoden ja kuukauden mukaan
└── unknow/             ← tiedostot ilman tunnistettavaa päivämäärää (säilyvät manuaalista tarkistusta varten)
```

## Usein kysytyt kysymykset

**K: Voiko tiedostojani korvautua tai kadota?**
Ei. Samannimiset tiedostot verrataan ensin sisällöltään: lähde poistetaan vain, jos sisältö on identtinen; muuten tiedosto nimetään uudelleen (numerolisalla päätteellä).

**K: Mitä tapahtuu, jos peruutan kesken?**
Jo lajiteltu osa säilyy, käsittelemättömät tiedostot jäävät koskemattomiksi, eikä tyhjiä kansioita poisteta.

**K: Jotkin tiedostot päätyvät kansioon "unknow". Mitä voin tehdä?**
Nimeä tiedosto uudelleen niin, että nimessä on päivämäärä, esim.:
- `2023_05_01` (alaviivoilla erotettuna)
- `20230501` (numerot peräkkäin)
Jos sitä ei edelleenkään tunnisteta, käsittele tiedosto manuaalisesti tai ota yhteys tekijään.

---
Tekijän yhteystiedot: 825772667@qq.com

---

## ⚠️ Tärkeä huomautus (lue ensin)

Tämä ohjelma **siirtää tiedostoja, poistaa kaksoiskappaleita ja poistaa tyhjiä kansioita**. Menetysten välttämiseksi:

1. **Varmuuskopioi ensin**: kopioi tärkeät valokuvat ja videot muualle ennen ensimmäistä käyttöä.
2. **Testaa ensin pienessä mittakaavassa**: kokeile epätärkeällä kansiolla ja tarkista tulos ennen kaikkien lajittelua.
3. **Valitse kohdesijainti huolellisesti**: käytä erillistä tyhjää kansiota, älä Työpöytää tai järjestelmälevyn juurta.

**Vastuuvapauslauseke**: Ohjelma toimitetaan "sellaisena kuin se on". Tekijä on tehnyt parhaansa lajittelulogiikan oikeellisuuden eteen, mutta ei ota vastuuta tiedostojen katoamisesta, vaurioitumisesta tai vahingossa poistamisesta. Ohjelman käyttö merkitsee tämän huomautuksen hyväksymistä.

//--------------Português--------------

# Maozai Photo Organizer Manual do usuário

Organiza fotos, vídeos e gravações de áudio espalhados em pastas, classificando por data em pastas organizadas, e remove automaticamente duplicatas e pastas vazias.

**Palavras-chave**: Maozai Photo Organizer, organizar fotos, organizar álbuns, ordenar fotos por data, organizar vídeos, apagar fotos duplicadas, organizar fotos do celular, organizar arquivos de áudio

---

## Problemas que resolve

- Fotos e vídeos bagunçados → classificados automaticamente por **ano/ano_mês**
- Capturas de tela demais → pasta **screenshot** separada
- Gravações de áudio → pastas **audio/ano_mês**
- O mesmo arquivo salvo várias vezes → duplicatas são detectadas e removidas

## Como usar (3 passos)

1. **Escolha a pasta de origem**: onde estão suas fotos/vídeos
2. **Escolha a pasta de saída**: para onde vai o resultado
3. Clique em **Iniciar** e aguarde a conclusão (é possível pausar, retomar ou cancelar)

## Como fica o resultado

```
Pasta de saída/
├── 2020/2020_5/        ← fotos e vídeos de maio de 2020
├── 2021/2021_10/
├── screenshot/2023/    ← capturas de tela, por ano
├── audio/2025_3/       ← arquivos de áudio, por ano e mês
└── unknow/             ← arquivos sem data reconhecível (mantidos para revisão manual)
```

## Perguntas frequentes

**P: Meus arquivos podem ser sobrescritos ou perdidos?**
Não. Arquivos com o mesmo nome são comparados primeiro pelo conteúdo: a origem só é apagada se o conteúdo for idêntico; caso contrário, o arquivo é renomeado (com sufixo numérico).

**P: O que acontece se eu cancelar no meio?**
A parte já organizada é mantida, os arquivos não processados ficam intactos e as pastas vazias não são apagadas.

**P: Alguns arquivos vão para "unknow". O que fazer?**
Renomeie o arquivo incluindo uma data no nome, por exemplo:
- `2023_05_01` (com sublinhados)
- `20230501` (dígitos seguidos)
Se ainda assim não for reconhecido, trate manualmente ou contate o autor.

---
Contato do autor: 825772667@qq.com

---

## ⚠️ Aviso importante (leia primeiro)

Este software **move arquivos, apaga duplicatas e apaga pastas vazias**. Para evitar perdas:

1. **Faça backup primeiro**: antes do primeiro uso, copie suas fotos e vídeos importantes para outro lugar.
2. **Teste primeiro em pequena escala**: teste com uma pasta sem importância e confira o resultado antes de organizar tudo.
3. **Escolha bem o local de saída**: use uma pasta vazia dedicada, não a Área de Trabalho nem a raiz do disco do sistema.

**Isenção de responsabilidade**: Este software é fornecido "no estado em que se encontra". O autor fez o possível para garantir a correção da organização, mas não se responsabiliza por perda, dano ou exclusão acidental de arquivos. Ao usar o software, você aceita este aviso.

//--------------Polski--------------

# Maozai Photo Organizer Instrukcja obsługi

Sortuje zdjęcia, filmy i nagrania audio rozrzucone po folderach według daty wykonania do uporządkowanych folderów oraz automatycznie usuwa duplikaty i puste foldery.

**Słowa kluczowe**: Maozai Photo Organizer, sortowanie zdjęć, organizowanie albumów, sortowanie zdjęć po dacie, sortowanie filmów, usuwanie duplikatów zdjęć, organizowanie zdjęć z telefonu, sortowanie plików audio

---

## Jakie problemy rozwiązuje

- Zdjęcia i filmy w nieładzie → automatycznie posortowane według **rok/rok_miesiąc**
- Za dużo zrzutów ekranu → przenoszone do osobnego folderu **screenshot**
- Nagrania audio → przenoszone do folderów **audio/rok_miesiąc**
- Ten sam plik zapisany kilka razy → duplikaty są wykrywane i usuwane

## Jak używać (3 kroki)

1. **Wybierz folder źródłowy**: gdzie znajdują się Twoje zdjęcia/filmy
2. **Wybierz folder docelowy**: gdzie trafi posortowany wynik
3. Kliknij **Start** i poczekaj na zakończenie (można wstrzymać, wznowić lub anulować)

## Tak wygląda wynik

```
Folder docelowy/
├── 2020/2020_5/        ← zdjęcia i filmy z maja 2020
├── 2021/2021_10/
├── screenshot/2023/    ← zrzuty ekranu, według roku
├── audio/2025_3/       ← pliki audio, według roku i miesiąca
└── unknow/             ← pliki bez rozpoznawalnej daty (zachowane do ręcznej kontroli)
```

## Częste pytania

**P: Czy moje pliki mogą zostać nadpisane lub utracone?**
Nie. Pliki o tej samej nazwie są najpierw porównywane pod względem treści: źródło jest usuwane tylko przy identycznej treści; w przeciwnym razie plik jest przemianowywany (z przyrostkiem liczbowym).

**P: Co się stanie, jeśli anuluję w połowie?**
Posortowana część zostaje zachowana, nieprzetworzone pliki pozostają nietknięte, a puste foldery nie są usuwane.

**P: Niektóre pliki trafiają do „unknow". Co mogę zrobić?**
Zmień nazwę pliku tak, aby zawierała datę, np.:
- `2023_05_01` (z podkreśleniami)
- `20230501` (cyfry razem)
Jeśli nadal nie zostanie rozpoznany, obsłuż go ręcznie lub skontaktuj się z autorem.

---
Kontakt do autora: 825772667@qq.com

---

## ⚠️ Ważna informacja (przeczytaj najpierw)

To oprogramowanie **przenosi pliki, usuwa duplikaty i usuwa puste foldery**. Aby uniknąć strat:

1. **Najpierw zrób kopię zapasową**: przed pierwszym użyciem skopiuj ważne zdjęcia i filmy w inne miejsce.
2. **Najpierw przetestuj na małej skali**: wypróbuj na nieważnym folderze i sprawdź wynik, zanim posortujesz wszystko.
3. **Dokładnie wybierz lokalizację docelową**: użyj dedykowanego pustego folderu, nie Pulpitu ani katalogu głównego dysku systemowego.

**Zastrzeżenie**: Oprogramowanie jest dostarczane „tak jak jest". Autor dołożył wszelkich starań, aby logika sortowania była poprawna, ale nie ponosi odpowiedzialności za utratę, uszkodzenie lub przypadkowe usunięcie plików. Korzystanie z oprogramowania oznacza akceptację tej informacji.

//--------------Čeština--------------

# Maozai Photo Organizer Uživatelská příručka

Třídí fotky, videa a zvukové nahrávky roztroušené po složkách podle data pořízení do přehledných složek a automaticky odstraňuje duplikáty a prázdné složky.

**Klíčová slova**: Maozai Photo Organizer, třídit fotky, organizovat alba, třídit fotky podle data, třídit videa, mazat duplicitní fotky, organizovat fotky z telefonu, třídit zvukové soubory

---

## Jaké problémy řeší

- Fotky a videa v nepořádku → automaticky seřazené podle **rok/rok_měsíc**
- Příliš mnoho snímků obrazovky → přesunuty do samostatné složky **screenshot**
- Zvukové nahrávky → přesunuty do složek **audio/rok_měsíc**
- Stejný soubor uložen vícekrát → duplikáty jsou rozpoznány a odstraněny

## Jak se používá (3 kroky)

1. **Vyberte zdrojovou složku**: kde jsou vaše fotky/videa
2. **Vyberte výstupní složku**: kam se umístí výsledek
3. Klikněte na **Spustit** a počkejte na dokončení (lze pozastavit, pokračovat nebo zrušit)

## Jak vypadá výsledek

```
Výstupní složka/
├── 2020/2020_5/        ← fotky a videa z května 2020
├── 2021/2021_10/
├── screenshot/2023/    ← snímky obrazovky, podle roku
├── audio/2025_3/       ← zvukové soubory, podle roku a měsíce
└── unknow/             ← soubory bez rozpoznatelného data (zachované k ruční kontrole)
```

## Časté dotazy

**O: Mohou se mé soubory přepsat nebo ztratit?**
Ne. Soubory se stejným názvem se nejprve porovnají podle obsahu: zdroj se smaže jen při identickém obsahu; jinak se soubor přejmenuje (s číselnou příponou).

**O: Co se stane, když to zruším uprostřed?**
Setříděná část zůstane zachována, nezpracované soubory zůstanou nedotčeny a prázdné složky se nesmažou.

**O: Některé soubory skončí ve složce „unknow". Co s nimi?**
Přejmenujte soubor tak, aby název obsahoval datum, např.:
- `2023_05_01` (s podtržítky)
- `20230501` (číslice za sebou)
Pokud ani tak není rozpoznán, zpracujte jej ručně nebo kontaktujte autora.

---
Kontakt na autora: 825772667@qq.com

---

## ⚠️ Důležité upozornění (přečtěte nejdříve)

Tento software **přesouvá soubory, maže duplikáty a maže prázdné složky**. Abyste předešli ztrátám:

1. **Nejdříve zálohujte**: před prvním použitím si zkopírujte důležité fotky a videa jinam.
2. **Nejdřív vyzkoušejte na malém vzorku**: otestujte na nedůležité složce a ověřte výsledek, než setřídíte vše.
3. **Pečlivě zvolte výstupní umístění**: použijte vyhrazenou prázdnou složku, ne Plochu ani kořen systémového disku.

**Vyloučení odpovědnosti**: Software je poskytován „tak, jak je". Autor učinil maximum pro správnost třídění, ale nenese odpovědnost za ztrátu, poškození nebo nechtěné smazání souborů. Použitím softwaru toto upozornění přijímáte.

//--------------العربية--------------

# Maozai Photo Organizer دليل المستخدم

يرتب الصور ومقاطع الفيديو والتسجيلات الصوتية المبعثرة في المجلدات حسب تاريخ الالتقاط في مجلدات منظمة، ويحذف تلقائيًا الملفات المكررة والمجلدات الفارغة.

**الكلمات المفتاحية**: Maozai Photo Organizer، ترتيب الصور، تنظيم الألبومات، فرز الصور حسب التاريخ، ترتيب الفيديوهات، حذف الصور المكررة، تنظيم صور الهاتف، ترتيب الملفات الصوتية

---

## المشكلات التي يحلها

- الصور والفيديوهات مبعثرة بشكل عشوائي → تُفرز تلقائيًا حسب **السنة/السنة_الشهر**
- لقطات شاشة كثيرة جدًا → تُنقل إلى مجلد **screenshot** منفصل
- التسجيلات الصوتية → تُنقل إلى مجلدات **audio/السنة_الشهر**
- نفس الملف محفوظ عدة مرات → تُكتشف المكررات وتُحذف

## طريقة الاستخدام (3 خطوات)

1. **اختر مجلد المصدر**: حيث توجد صورك/فيديوهاتك
2. **اختر مجلد الإخراج**: أين توضع النتيجة المرتبة
3. اضغط **ابدأ** وانتظر الانتهاء (يمكن الإيقاف المؤقت أو الاستئناف أو الإلغاء)

## شكل النتيجة

```
مجلد الإخراج/
├── 2020/2020_5/        ← صور وفيديوهات مايو 2020
├── 2021/2021_10/
├── screenshot/2023/    ← لقطات الشاشة حسب السنة
├── audio/2025_3/       ← الملفات الصوتية حسب السنة والشهر
└── unknow/             ← ملفات بدون تاريخ معروف (تُحفظ للمراجعة اليدوية)
```

## الأسئلة الشائعة

**س: هل يمكن أن تُستبدل ملفاتي أو تُفقد؟**
لا. الملفات بنفس الاسم تُقارن أولاً بالمحتوى: لا يُحذف المصدر إلا إذا كان المحتوى متطابقًا تمامًا؛ وإلا يُعاد تسمية الملف (مع لاحقة رقمية).

**س: ماذا يحدث إذا ألغيت في المنتصف؟**
يبقى الجزء المرتب كما هو، والملفات غير المعالجة لا تُمس، والمجلدات الفارغة لا تُحذف.

**س: بعض الملفات تذهب إلى "unknow". ماذا أفعل؟**
أعد تسمية الملف ليتضمن تاريخًا في الاسم، مثال:
- `2023_05_01` (بشرطات سفلية)
- `20230501` (أرقام متتالية)
إذا لم يُتعرف عليه بعد، عالجه يدويًا أو تواصل مع المؤلف.

---
للتواصل مع المؤلف: 825772667@qq.com

---

## ⚠️ تنبيه مهم (اقرأ أولاً)

هذا البرنامج **ينقل الملفات ويحذف المكررات ويحذف المجلدات الفارغة**. لتجنب أي فقدان:

1. **انسخ احتياطيًا أولاً**: قبل الاستخدام الأول، انسخ صورك وفيديوهاتك المهمة إلى مكان آخر.
2. **جرّب أولاً على نطاق صغير**: جرّب على مجلد غير مهم وتحقق من النتيجة قبل ترتيب كل شيء.
3. **اختر موقع الإخراج بعناية**: استخدم مجلدًا فارغًا مخصصًا، وليس سطح المكتب أو جذر قرص النظام.

**إخلاء مسؤولية**: يُقدم هذا البرنامج "كما هو". بذل المؤلف قصارى جهده لضمان صحة منطق الترتيب، لكنه لا يتحمل أي مسؤولية عن فقدان أو تلف أو حذف عرضي للملفات. استخدامك للبرنامج يعني موافقتك على هذا التنبيه.

//--------------Türkçe--------------

# Maozai Photo Organizer Kullanım Kılavuzu

Klasörlere dağılmış fotoğrafları, videoları ve ses kayıtlarını çekim tarihine göre düzenli klasörlere otomatik olarak sıralar; kopyaları ve boş klasörleri otomatik temizler.

**Anahtar kelimeler**: Maozai Photo Organizer, fotoğraf düzenleme, albüm düzenleme, tarihe göre fotoğraf sıralama, video düzenleme, yinelenen fotoğrafları silme, telefon fotoğraflarını düzenleme, ses dosyalarını düzenleme

---

## Hangi sorunları çözer

- Fotoğraflar ve videolar dağınık → **yıl/yıl_ay** olarak otomatik sıralanır
- Çok fazla ekran görüntüsü → ayrı bir **screenshot** klasörüne taşınır
- Ses kayıtları → **audio/yıl_ay** klasörlerine taşınır
- Aynı dosya birden çok kez kaydedilmiş → kopyalar algılanır ve silinir

## Nasıl kullanılır (3 adım)

1. **Kaynak klasörü seçin**: fotoğraflarınızın/videolarınızın olduğu klasör
2. **Çıktı klasörünü seçin**: sıralanmış sonucun gideceği yer
3. **Başlat**'a tıklayın ve bitmesini bekleyin (duraklatma, sürdürme veya iptal mümkün)

## Sonuç nasıl görünür

```
Çıktı klasörü/
├── 2020/2020_5/        ← Mayıs 2020'de çekilen fotoğraf ve videolar
├── 2021/2021_10/
├── screenshot/2023/    ← ekran görüntüleri, yıla göre
├── audio/2025_3/       ← ses dosyaları, yıl ve aya göre
└── unknow/             ← tarihi tanınamayan dosyalar (elle inceleme için saklanır)
```

## Sık sorulan sorular

**S: Dosyalarım üzerine yazılır mı ya da kaybolur mu?**
Hayır. Aynı ada sahip dosyalar önce içerik olarak karşılaştırılır: kaynak yalnızca içerik birebir aynıysa silinir; aksi halde dosya yeniden adlandırılır (sayı ekiyle).

**S: Yarıda iptal edersem ne olur?**
Sıralanan kısım korunur, işlenmemiş dosyalar olduğu gibi kalır ve boş klasörler silinmez.

**S: Bazı dosyalar "unknow" klasörüne gidiyor. Ne yapabilirim?**
Dosyayı, adında tarih olacak şekilde yeniden adlandırın, örneğin:
- `2023_05_01` (alt çizgili)
- `20230501` (bitişik rakamlar)
Yine de tanınmıyorsa dosyayı elle işleyin veya yazara başvurun.

---
Yazar iletişim: 825772667@qq.com

---

## ⚠️ Önemli uyarı (önce okuyun)

Bu yazılım **dosya taşır, kopyaları siler ve boş klasörleri siler**. Kayıpları önlemek için:

1. **Önce yedekleyin**: ilk kullanımdan önce önemli fotoğraf ve videolarınızı başka bir yere kopyalayın.
2. **Önce küçük çapta deneyin**: önemsiz bir klasörle deneyip sonucu doğrulamadan her şeyi sıralamayın.
3. **Çıktı konumunu dikkatli seçin**: Masaüstü veya sistem diski kökü yerine ayrılmış boş bir klasör kullanın.

**Sorumluluk reddi**: Bu yazılım "olduğu gibi" sunulur. Yazar, sıralama mantığının doğruluğu için elinden geleni yapmıştır ancak dosya kaybı, hasarı veya yanlışlıkla silinmesinden sorumlu tutulamaz. Yazılımı kullanarak bu uyarıyı kabul etmiş olursunuz.

//--------------ภาษาไทย--------------

# Maozai Photo Organizer คู่มือการใช้งาน

จัดเรียงรูปภาพ วิดีโอ และไฟล์เสียงที่กระจัดกระจายในโฟลเดอร์ต่าง ๆ ตามวันที่ถ่าย ไปยังโฟลเดอร์ที่เป็นระเบียบโดยอัตโนมัติ พร้อมลบไฟล์ซ้ำและโฟลเดอร์ว่าง

**คำค้นหา**: Maozai Photo Organizer, จัดระเบียบรูปภาพ, จัดระเบียบอัลบั้ม, จัดเรียงรูปตามวันที่, จัดระเบียบวิดีโอ, ลบรูปภาพซ้ำ, จัดระเบียบรูปจากมือถือ, จัดระเบียบไฟล์เสียง

---

## ช่วยแก้ปัญหาอะไรได้บ้าง

- รูปและวิดีโอกระจัดกระจาย → จัดเรียงอัตโนมัติตาม **ปี/ปี_เดือน**
- ภาพหน้าจอเยอะเกินไป → ย้ายไปโฟลเดอร์ **screenshot** แยกต่างหาก
- ไฟล์เสียง → ย้ายไปโฟลเดอร์ **audio/ปี_เดือน**
- ไฟล์เดียวกันบันทึกหลายครั้ง → ตรวจพบและลบไฟล์ซ้ำอัตโนมัติ

## วิธีใช้ (3 ขั้นตอน)

1. **เลือกโฟลเดอร์ต้นทาง**: ที่เก็บรูป/วิดีโอของคุณ
2. **เลือกโฟลเดอร์ปลายทาง**: ที่จะเก็บผลลัพธ์ที่จัดเรียงแล้ว
3. กด **เริ่ม** แล้วรอจนเสร็จ (หยุดชั่วคราว ทำต่อ หรือยกเลิกได้)

## ผลลัพธ์หลังจัดเรียง

```
โฟลเดอร์ปลายทาง/
├── 2020/2020_5/        ← รูปและวิดีโอที่ถ่ายเดือนพฤษภาคม 2020
├── 2021/2021_10/
├── screenshot/2023/    ← ภาพหน้าจอ จัดตามปี
├── audio/2025_3/       ← ไฟล์เสียง จัดตามปีและเดือน
└── unknow/             ← ไฟล์ที่ระบุวันที่ไม่ได้ (เก็บไว้ให้ตรวจสอบเอง)
```

## คำถามที่พบบ่อย

**ถาม: ไฟล์ของฉันจะถูกเขียนทับหรือหายไปไหม?**
ไม่ ไฟล์ชื่อเดียวกันจะถูกเปรียบเทียบเนื้อหาก่อน: ลบต้นฉบับเฉพาะเมื่อเนื้อหาเหมือนกันทุกประการเท่านั้น มิฉะนั้นไฟล์จะถูกเปลี่ยนชื่อ (เติมเลขต่อท้าย)

**ถาม: ถ้ายกเลิกกลางทางจะเกิดอะไรขึ้น?**
ส่วนที่จัดแล้วยังคงอยู่ ไฟล์ที่ยังไม่ได้ประมวลผลจะไม่ถูกแตะต้อง และโฟลเดอร์ว่างจะไม่ถูกลบ

**ถาม: บางไฟล์ไปอยู่ใน "unknow" ต้องทำอย่างไร?**
เปลี่ยนชื่อไฟล์ให้มีวันที่อยู่ในชื่อ เช่น:
- `2023_05_01` (คั่นด้วยขีดล่าง)
- `20230501` (ตัวเลขต่อกัน)
หากยังระบุไม่ได้ โปรดจัดการด้วยตนเองหรือติดต่อผู้พัฒนา

---
ติดต่อผู้พัฒนา: 825772667@qq.com

---

## ⚠️ ข้อควรทราบสำคัญ (โปรดอ่านก่อน)

ซอฟต์แวร์นี้จะ **ย้ายไฟล์ ลบไฟล์ซ้ำ และลบโฟลเดอร์ว่าง** เพื่อป้องกันความสูญเสีย:

1. **สำรองข้อมูลก่อน**: ก่อนใช้งานครั้งแรก ให้คัดลอกรูปและวิดีโอสำคัญไปไว้ที่อื่น
2. **ทดลองกับโฟลเดอร์เล็กก่อน**: ลองกับโฟลเดอร์ที่ไม่สำคัญ ตรวจสอบผลลัพธ์ให้พอใจก่อนจัดเรียงทั้งหมด
3. **เลือกตำแหน่งปลายทางให้รอบคอบ**: ใช้โฟลเดอร์ว่างเฉพาะ ไม่ใช่เดสก์ท็อปหรือรากของไดรฟ์ระบบ

**ข้อจำกัดความรับผิดชอบ**: ซอฟต์แวร์นี้จัดเตรียม "ตามสภาพ" ผู้พัฒนาได้พยายามอย่างเต็มที่เพื่อให้การจัดเรียงถูกต้อง แต่ไม่รับผิดชอบต่อการสูญหาย เสียหาย หรือถูกลบโดยไม่ตั้งใจของไฟล์ใด ๆ การใช้งานซอฟต์แวร์ถือว่าคุณยอมรับข้อความนี้



