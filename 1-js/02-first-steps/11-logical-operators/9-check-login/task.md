الأهمية: 3

---

# فحص تسجيل الدخول

أكتب كود يكلب تسجيل الدخول باستخدام `prompt`.

إذا كتب المستخدم كلمة `"Admin"` اطلب منه `prompt` كلمة المرور فإذا كتب سطر فارغ أو استخدم `key:Esc` -- أظهر رسالة "Canceled" وإذا كان نص آخر أظهر له "I don't know you".

يتم فحص كلمة المرور كالتالي:

- إذا كانت تساوي "TheMaster" يتم عرض "Welcome!",
- نص آخر يتم عرض "Wrong password",
- نص فارغ أو إلغاء العملية يتم عرض "Canceled"

الصيغة العامة:

![](ifelse_task.svg)

استخدم تعبيرات `if` متداخلة. انتبه أن يكون الكود مقروء.

ملحوظة:  تمرير نص فارغ إلى prompt يرجع نص فارغ `''`. تمرير `key:ESC` يرجع `null`.

[demo]
