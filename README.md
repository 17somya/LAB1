# Android Lab 1 – Tap Counter

Submitted by: **Somya Thakkar**

**Tap Counter** is a simple Android app that shows a large counter and a button. Each tap on the button increments the count. The screen also includes a friendly image and a styled header.

Time spent: **2** hours in total
## Required Features

The following **required** functionality is completed:

- [x] Counter value is displayed on screen
- [x] Tapping the button increments the counter
- [x] Layout built with `ConstraintLayout` and includes an image

### Optional Enhancements

- [ ] Long-press to reset the counter
- [ ] Toast or Snackbar feedback on tap/reset
- [x] Customized colors and typography for the header and background
- [x] Added `contentDescription` for images (accessibility)
- [ ] Used View Binding instead of `findViewById`
- [ ] Customized launch screen (splash) color/icon

---

## Video Walkthrough

Here's a walkthrough of the implemented features:

![LAB_1](https://github.com/user-attachments/assets/0485c879-3559-4b81-8602-f54118c0d982)

![LAB_1(2)](https://github.com/user-attachments/assets/a8f575ae-e1f2-4044-a523-e50678b78661)

https://imgur.com/mG3e48N

---

## How to Run

1. Open the project in **Android Studio (Koala)**.
2. Click **Sync Project with Gradle Files**.
3. Run on an emulator or physical device (API 24+ recommended).
4. Tap the button to increase the counter.

---

## Notes

- If the counter or button didn’t appear as expected, adding proper `ConstraintLayout` constraints (top/bottom/start/end) fixed the layout.
- If click handling didn’t work initially, verifying the correct `onClick` binding or attaching a `setOnClickListener` in `onCreate` resolved it.

---

## License
Copyright 2025 Somya Thakkar
