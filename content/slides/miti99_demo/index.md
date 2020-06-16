---
title: Slides
summary: Giới thiệu tính năng Slides.
authors: []
tags: []
categories: []
date: "2019-02-05T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

## Cách tạo một slide trình chiếu trên web của chúng ta

Thật ra là mình cũng dựa trên một nguồn có sẵn thôi :v

[Xem ở đây](https://github.com/hakimel/reveal.js)

---

## Tính năng

- Viết slide ngay trong Markdown
- Viết, trình chiếu slide của chúng ta
- Có tính năng "speaker notes" (chia 2 màn hình như PPT ấy)
- Dùng được cho điện thoại

---

## Cách điều khiển

- Slide kế: `mũi tên phải` hoặc `phím cách (space)`
- Slide trước: `mũi tên trái`
- Slide đầu: `Home`
- Slide cuối: `End`
- Xem tổng quan: `Esc`
- Bật "Speaker notes": `S`
- Toàn màn hình: `F`
- Zoom: `Ctrl + Click`
- [Xuất file PDF](https://github.com/hakimel/reveal.js#pdf-export): `E`

---

## Code Highlighting

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Này nhé, cùng đếm một, hai, ba nào!

```html
{{%/* fragment */%}} Một {{%/* /fragment */%}}
{{%/* fragment */%}} **Hai** {{%/* /fragment */%}}
{{%/* fragment */%}} Ba {{%/* /fragment */%}}
```

Nhấn `Space` để bắt đầu nhé!

{{% fragment %}} Một {{% /fragment %}}
{{% fragment %}} **Hai** {{% /fragment %}}
{{% fragment %}} Ba {{% /fragment %}}

---

Một fragment thì có 2 parameters tùy chọn:

- `class`: Dùng một style tùy chọn
- `weight`: Sắp thứ tự

---

## Speaker Notes

Để thêm speaker notes thì làm như sau:

```markdown
{{%/* speaker_note */%}}
- Chỉ người trình bày mới đọc đươc cái này
- Nhấn `S` để xem thử
{{%/* /speaker_note */%}}
```

Nhấn `S` để xem thử nhé!

{{< speaker_note >}}

- Chỉ người trình bày mới đọc đươc cái này
- Nhấn `S` để xem thử
{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/img/boards.jpg" >}}

## Custom Slide

Này là slide tùy chọn nè

```markdown
{{</* slide background-image="/img/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Lấy theme navy làm mẫu nha. Tại vì có chữ "Vy" đó :v

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

## Câu hỏi

Muốn hòi mình gì nào? Inbox group chat của nhóm mình đi. Hiu quạnh lâu nay :/

[BKFC - THPT Đức Hòa](https://www.facebook.com/messages/t/2025327994248797)
