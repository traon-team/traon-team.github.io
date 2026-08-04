#   PassMan

PassMan is a simple password manager.

-   The app can generate random passwords. They will be stored and protected via your master password.
-   Your master password is hashed via [Argon2][site:argon2] password-hashing algorithm.
-   The hashed-password is then used to encrypt database via [XChaCha20-Poly1305][site:xchacha20-poly1305] algorithm.

Languages supported: Persian, Chinese, Russian, English.

##  Downloads

| Operating System | Version                              | Release Date | Notes
| ---------------- | ------------------------------------ | ------------ | -----
| Android          | [`0.2.10`/Internet][apk:auto-update] | `2026-08-04` | Internet permission is required for the auto-update functionality, which operates independently of any app store.
| Android          | [`0.2.10`][apk:no-internet]          | `2026-08-04` | No Internet permission needed.

##  Android screenshots

![](pass-man/screenshots/android/0.2.0/00.png)

![](pass-man/screenshots/android/0.2.0/01.png)

![](pass-man/screenshots/android/0.2.0/02.png)

![](pass-man/screenshots/android/0.2.0/03.png)

![](pass-man/screenshots/android/0.2.0/04.png)

![](pass-man/screenshots/android/0.2.0/05.png)

[apk:auto-update]: https://drive.google.com/file/d/1UTWkXd-zCgE4wxF9Hl5qh8PAQXVgWc0y/view?usp=sharing
[apk:no-internet]: https://drive.google.com/file/d/1ggoEZ0JxZeHt6cn-T0MJ--NeyjnhWsaF/view?usp=sharing
[site:argon2]: https://www.cryptolux.org/index.php/Argon2
[site:xchacha20-poly1305]: https://en.wikipedia.org/wiki/ChaCha20-Poly1305
