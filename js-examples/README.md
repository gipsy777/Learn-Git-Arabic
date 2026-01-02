# أمثلة JavaScript AJAX
# JavaScript AJAX Examples

هذا المجلد يحتوي على أمثلة عملية لكيفية استخدام AJAX في JavaScript لإرسال واستقبال البيانات من الخادم.

This folder contains practical examples of how to use AJAX in JavaScript to send and receive data from the server.

---

## المحتويات | Contents

### 1. ajax-get-example.html
**مثال طلبات GET | GET Requests Example**

يوضح هذا الملف ثلاث طرق مختلفة لإجراء طلبات GET:

This file demonstrates three different ways to make GET requests:

- **XMLHttpRequest الكلاسيكي | Classic XMLHttpRequest**: الطريقة التقليدية لإجراء طلبات AJAX
  - Traditional method for making AJAX requests
  
- **Fetch API**: الطريقة الحديثة المبنية على Promises
  - Modern Promise-based approach
  
- **Async/Await**: أحدث طريقة لكتابة كود غير متزامن بشكل متزامن
  - Latest way to write asynchronous code synchronously

**الميزات | Features:**
- جلب بيانات مستخدم واحد | Fetch single user data
- جلب منشور واحد | Fetch single post
- جلب قائمة بجميع المستخدمين | Fetch list of all users
- معالجة الأخطاء | Error handling
- حالات التحميل | Loading states
- واجهة مستخدم باللغة العربية | Arabic user interface

---

### 2. ajax-post-example.html
**مثال طلبات POST | POST Requests Example**

يوضح هذا الملف كيفية إرسال البيانات إلى الخادم باستخدام طرق مختلفة:

This file demonstrates how to send data to the server using different methods:

- **XMLHttpRequest مع JSON**: إرسال بيانات بصيغة JSON
  - Send data in JSON format
  
- **Fetch API مع JSON**: الطريقة الحديثة لإرسال JSON
  - Modern way to send JSON
  
- **FormData**: إرسال بيانات النماذج
  - Send form data

**الميزات | Features:**
- نموذج إنشاء منشور جديد | Create new post form
- إرسال بيانات مستخدم | Send user data
- إرسال بيانات FormData | Send FormData
- معالجة الاستجابات | Response handling
- عرض البيانات المُرسلة والمُستقبلة | Display sent and received data
- واجهة مستخدم باللغة العربية | Arabic user interface

---

## كيفية الاستخدام | How to Use

1. **فتح الملفات في المتصفح | Open files in browser:**
   - ببساطة افتح أي ملف HTML في متصفح الويب الخاص بك
   - Simply open any HTML file in your web browser

2. **لا حاجة لخادم | No server needed:**
   - الأمثلة تستخدم JSONPlaceholder API العام
   - Examples use the public JSONPlaceholder API
   - يمكن تشغيلها مباشرة من نظام الملفات
   - Can be run directly from the file system

3. **الاستكشاف | Exploration:**
   - جرب الأزرار المختلفة لرؤية كيف تعمل طلبات AJAX
   - Try different buttons to see how AJAX requests work
   - افتح أدوات المطور (F12) لرؤية طلبات الشبكة
   - Open Developer Tools (F12) to see network requests
   - راجع الكود المصدري لفهم التنفيذ
   - Review the source code to understand the implementation

---

## API المستخدم | Used API

جميع الأمثلة تستخدم **JSONPlaceholder** - API مجاني وهمي للاختبار والنماذج الأولية.

All examples use **JSONPlaceholder** - a free fake API for testing and prototyping.

🔗 https://jsonplaceholder.typicode.com

**ملاحظة مهمة | Important Note:**
- البيانات المُرسلة لن تُحفظ فعلياً على الخادم
- Sent data won't actually be saved on the server
- الـ API يقوم بمحاكاة الاستجابات فقط
- The API only simulates responses

---

## المفاهيم المشروحة | Concepts Explained

### AJAX (Asynchronous JavaScript and XML)
تقنية تسمح لصفحات الويب بالتحديث بشكل غير متزامن من خلال تبادل البيانات مع خادم الويب في الخلفية.

A technique that allows web pages to update asynchronously by exchanging data with a web server in the background.

### XMLHttpRequest
الكائن الكلاسيكي المستخدم لإجراء طلبات HTTP في JavaScript.

The classic object used to make HTTP requests in JavaScript.

### Fetch API
واجهة برمجية حديثة توفر طريقة أسهل وأقوى لإجراء طلبات HTTP.

Modern interface that provides an easier and more powerful way to make HTTP requests.

### Promises & Async/Await
أنماط برمجية لمعالجة العمليات غير المتزامنة بطريقة أكثر قابلية للقراءة.

Programming patterns for handling asynchronous operations in a more readable way.

### HTTP Methods
- **GET**: لجلب البيانات من الخادم | To fetch data from the server
- **POST**: لإرسال بيانات جديدة إلى الخادم | To send new data to the server

---

## التوافق مع المتصفحات | Browser Compatibility

- **XMLHttpRequest**: مدعوم في جميع المتصفحات الحديثة والقديمة
  - Supported in all modern and old browsers
  
- **Fetch API**: مدعوم في المتصفحات الحديثة (IE 11 غير مدعوم)
  - Supported in modern browsers (IE 11 not supported)
  
- **Async/Await**: مدعوم في المتصفحات الحديثة (ES2017+)
  - Supported in modern browsers (ES2017+)

---

## موارد إضافية | Additional Resources

- [MDN - Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [MDN - XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
- [MDN - Async/Await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await)
- [JSONPlaceholder Guide](https://jsonplaceholder.typicode.com/guide/)

---

## الترخيص | License

هذه الأمثلة مفتوحة المصدر ومتاحة للاستخدام التعليمي.

These examples are open source and available for educational use.
