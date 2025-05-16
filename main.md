Fayllarni `C:/Users/User/Desktop/git exp` katalogidan `first-project` nomli GitHub repozitoriyasiga saqlash uchun quyidagi amallarni bajaring:

1. Terminal yoki buyruq satrini oching.
2. Katalogga o'ting:
    ```bash
    cd "C:/Users/User/Desktop/git exp"
    ```
3. Git repozitoriyasini initsializatsiya qiling:
    ```bash
    git init
    ```
4. Barcha fayllarni staging maydoniga qo'shing:
    ```bash
    git add .
    ```
5. O'zgarishlarni commit qiling:
    ```bash
    git commit -m "Initial commit"
    ```
6. GitHub'da `first-project` nomli yangi repozitoriya yarating (buni GitHub veb-sayti orqali qilishingiz mumkin).
7. Mahalliy repozitoriyani GitHub repozitoriyasiga bog'lang:
    ```bash
    git remote add origin https://github.com/<your-username>/first-project.git
    ```
    `<your-username>` o'rniga GitHub foydalanuvchi nomingizni yozing.
8. O'zgarishlarni GitHub'ga yuboring:
    ```bash
    git branch -M main
    git push -u origin main
    ```

Endi fayllaringiz `first-project` repozitoriyasida GitHub'da saqlangan.