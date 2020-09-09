---
title: "ওপেনবাংলা কিবোর্ড ১.৪.০ - প্রকাশিত!"
date: 2018-05-04
image: images/blog/post-2.jpg
author: Muhammad Mominul Huque
---

ওপেনবাংলা কিবোর্ডের এই সংস্করণ একটি রক্ষণাবেক্ষণমূলক বা "*maintenance release*", তাই এই সংস্করণে মূলত বাগ ফিক্সকে বেশী মূল্য দেয়া হয়েছে।
<!--more-->

ওপেনবাংলা কিবোর্ডের টপবার এখন প্রথমবারের মতো স্টার্ট করা হলে স্ক্রিনের মাঝে অবস্থান নেবে। ফলে এখন টপবার সহজেই ড্র্যাগ করা সম্ভব হবে। পূর্ববর্তী সংস্করণে টপবার প্রথমবারের মতো স্টার্ট করা হলে স্ক্রিনের কর্নারে অবস্থান করত ফলে অনেক সময় টপবার ড্র্যাগ করা সম্ভব হতো না। বাগটি এই সংস্করণে ফিক্স করা হয়েছে।

ওপেনবাংলা কিবোর্ড এখন স্বয়ংক্রিয়ভাবে নতুন আপডেটের জন্য ব্যবহারকারীকে অবহিত করবে। নতুন আপডেট পাওয়া গেলে ওপেনবাংলা কিবোর্ড ব্যবহারকারীকে জানাবে:
{{< figure src="/images/blog/update_notification.png" >}}

## ইন্সটলেশন
### উবুন্টু
ব্যবহারকারীরা উবুন্টু বা ডেবিয়ান বেসড যেকোন সিস্টেমে সহজেই ওপেনবাংলা কিবোর্ড ইন্সটল করতে পারবেন। [রিলিজ পেইজ](https://github.com/OpenBangla/OpenBangla-Keyboard/releases/tag/1.4.0) থেকে `deb` প্যাকেজ ডাউনলোড করে তা সফটওয়্যার ইন্সটলারের মাধ্যমে বা নিম্নের কমান্ডের মাধ্যমে ওপেনবাংলা কিবোর্ড ইন্সটল করতে হবে।
```bash
$ sudo apt install ./path/to/OpenBanglaKeyboard/package.deb
```
বিস্তারিত জানতে [উইকি](https://github.com/OpenBangla/OpenBangla-Keyboard/wiki/Installing-OpenBangla-Keyboard) ভিজিট করুন।
### ফেডোরা
ব্যবহারকারীরা ফেডোরা বা ফেডোরা বেসড যেকোন সিস্টেমে সহজেই ওপেনবাংলা কিবোর্ড ইন্সটল করতে পারবেন। [রিলিজ পেইজ](https://github.com/OpenBangla/OpenBangla-Keyboard/releases/tag/1.4.0) থেকে `rpm` প্যাকেজ ডাউনলোড করে তা সফটওয়্যার ইন্সটলারের মাধ্যমে বা নিম্নের কমান্ডের মাধ্যমে ওপেনবাংলা কিবোর্ড ইন্সটল করতে হবে।
```bash
$ sudo dnf install ./path/to/OpenBanglaKeyboard/package.rpm
```
বিস্তারিত জানতে [উইকি](https://github.com/OpenBangla/OpenBangla-Keyboard/wiki/Installing-OpenBangla-Keyboard) ভিজিট করুন।

ওপেনবাংলা কিবোর্ডের নতুন সংস্করণের সব পরিবর্তন জানতে [চেঞ্জলগ দেখুন](https://github.com/OpenBangla/OpenBangla-Keyboard/blob/master/CHANGELOG.md#140)।

**অনিবার্য কারণে আমরা [packagecloud.io](https://packagecloud.io/) এর মাধ্যমে ইন্সটলেশন সুবিধাটি বন্ধ করতে বাধ্য হয়েছি। তাই ব্যবহারকারীদের উপরে বর্ণিত নিয়মে ওপেনবাংলা কিবোর্ড ইন্সটল করতে হবে।**