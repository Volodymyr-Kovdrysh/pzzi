**Лабораторна робота 5: Тестування знищення даних**

**Мета:** Дослідити ефективність різних методів знищення даних, перевірити можливість відновлення видалених файлів і розробити рекомендації щодо безпечного видалення інформації.

**Завдання:**
1. Виконати тестове видалення файлів стандартними методами операційної системи.
2. Використати спеціалізовані інструменти для безпечного знищення даних.
3. Спробувати відновити видалені файли за допомогою програм для відновлення даних.
4. Проаналізувати ефективність методів знищення даних та надати рекомендації.
5. Оформити звіт із висновками.

---

### **1. Методи знищення даних** 🔥

#### **1.1 Стандартні методи видалення**
- Видалення файлів через «Кошик» у Windows/macOS або `rm` у Linux.
- Форматування диска через вбудовані засоби ОС (`format`, `mkfs`).

#### **1.2 Безпечне знищення файлів**
- **Windows**:
  - `sdelete` – безпечне видалення файлів шляхом перезапису.
  - BitLocker (шифрування перед видаленням).
- **Linux/macOS**:
  - `shred` – багаторазове перезаписування файлів.
  - `wipe` – очищення жорсткого диска від залишкових даних.
  - `dd if=/dev/zero of=/dev/sdX` – затирання всього диска.

#### **1.3 Фізичне знищення даних**
- Розмагнічування (degaussing).
- Фізичне пошкодження (дроблення, спалення, кислотне розчинення).

**Практичне завдання:**
- Виконати видалення тестових файлів за допомогою стандартних засобів.
- Перевірити можливість їх відновлення спеціальними утилітами.

---

### **2. Тестування відновлення даних** 🛠️

#### **2.1 Інструменти для відновлення**
- **Windows**:
  - Recuva
  - R-Studio
- **Linux/macOS**:
  - TestDisk
  - PhotoRec

**Практичне завдання:**
- Використати утиліти для спроби відновлення даних після стандартного видалення та безпечного затирання.
- Порівняти результати.

---

### **3. Аналіз ефективності методів** 📊

- Оцінити можливість відновлення після кожного способу видалення.
- Визначити найефективніший метод для кожного типу носія (HDD, SSD, флеш-накопичувачі).

**Практичне завдання:**
- Підготувати порівняльну таблицю ефективності методів видалення.
- Надати рекомендації щодо вибору оптимального методу для різних сценаріїв.

---

### **4. Оформлення звіту** 📄

**Зміст звіту:**
1. Вступ (мета, завдання роботи).
2. Опис використаних методів видалення та відновлення.
3. Результати тестування (знімки екрану, аналіз відновлення).
4. Висновки щодо ефективності методів та рекомендації.

**Очікуваний результат:**
- Розуміння процесу знищення даних і його наслідків.
- Практичні навички використання інструментів для безпечного видалення інформації.
- Розроблені рекомендації щодо вибору методів видалення.

---

### **Додаткові ресурси:**
- [Secure Data Disposal Guidelines (NIST)](https://csrc.nist.gov/publications/detail/sp/800-88/rev-1/final)
- [Recuva – Data Recovery](https://www.ccleaner.com/recuva)
- [TestDisk & PhotoRec Documentation](https://www.cgsecurity.org/)

