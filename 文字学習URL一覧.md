# 文字学習 URL 一覧

GitHub Pages でホスティング済み。**Macが起動していなくても**、iPadのSafariからいつでもアクセスできます。

**iPadでの開き方:** 下のURLをタップ、またはコピー → Safariのアドレスバーに貼り付けて開く。

**トップページ:**
<https://takutosquare00-max.github.io/moji-gakushu/>

---

## ひらがな

| 学習名 | URL |
|--------|-----|
| ひらがな ひつじゅん なぞりがき | <https://takutosquare00-max.github.io/hiragana-nazorigaki/> |

---

## カタカナ

| 学習名 | URL |
|--------|-----|
| カタカナ ひつじゅん なぞりがき | <https://takutosquare00-max.github.io/katakana-nazorigaki/> |

---

## 漢字

| 学習名 | URL |
|--------|-----|
| 漢字 N5（一年生・80字） | <https://takutosquare00-max.github.io/kanji-practice/1.一年生-N5/> |
| 漢字 N4（二年生・160字） | <https://takutosquare00-max.github.io/kanji-practice/2.二年生-N4-5/> |
| 漢字 N4（三年生・200字） | <https://takutosquare00-max.github.io/kanji-practice/3.三年生-N4/> |
| 漢字 N4（四年生・200字） | <https://takutosquare00-max.github.io/kanji-practice/4.四年生-N4/> |
| 漢字 N3（五年生・185字） | <https://takutosquare00-max.github.io/kanji-practice/5.五年生-N3/> |
| 漢字 N3（六年生・181字） | <https://takutosquare00-max.github.io/kanji-practice/6.六年生-N3-2/> |
| 漢字 N2 | （準備中） |
| 漢字 N1 | （準備中） |

---

## コピペ用（iPadのSafariで開く）

```
https://takutosquare00-max.github.io/moji-gakushu/
https://takutosquare00-max.github.io/hiragana-nazorigaki/
https://takutosquare00-max.github.io/katakana-nazorigaki/
https://takutosquare00-max.github.io/kanji-practice/
```

---

## 更新した場合

- **トップページ（moji-gakushu）:** `school/moji-gakushu/` 内で `git add . && git commit -m "更新" && git push`
- **ひらがな:** `school/ひらがな/1.ひらがな/` 内で同様に push
- **カタカナ:** `school/ひらがな/2.カタカナ/` 内で `git add . && git commit -m "更新" && git push`
- **漢字:** `school/kanji-deploy/` 内で以下を実行
  ```bash
  cp -r ../ひらがな/3.漢字/1.一年生-N5 ../ひらがな/3.漢字/2.二年生-N4-5 ../ひらがな/3.漢字/3.三年生-N4 ../ひらがな/3.漢字/4.四年生-N4 ../ひらがな/3.漢字/5.五年生-N3 ../ひらがな/3.漢字/6.六年生-N3-2 .
  git add . && git commit -m "教材更新" && git push
  ```
