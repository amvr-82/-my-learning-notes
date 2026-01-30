# سطح مقدماتی

## unit 2
Spread syntax (...):
در React، **Spread Syntax (`...`)** برای پاس دادن چندین prop به یک کامپوننت به‌صورت همزمان استفاده می‌شود و باعث **کاهش تکرار** و **خوانایی بیشتر کد** می‌شود.

---

## ✅ مثال ساده
```jsx
const userProps = {
  name: "Amirhossein",
  age: 22,
  role: "Frontend Developer",
};

<UserCard {...userProps} />


