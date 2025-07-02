# 📝 نظام إدارة التسجيل في الدورات التدريبية  
**Training Course Registration Management System**

هذا المشروع عبارة عن وحدة مخصصة تم تطويرها باستخدام Odoo، بهدف تسهيل إدارة الدورات التدريبية وتسجيل الطلاب فيها بطريقة منظمة وفعّالة.  
This project is a custom Odoo module developed to streamline the management of training courses and student registrations in an organized and efficient manner.

---

## 📌 وصف المشروع | Project Description

🔹 **بالعربية:**  
يقدّم النظام الإمكانيات التالية:
- إنشاء وتعديل بيانات الدورة التدريبية (الاسم، المدرب، التاريخ، عدد المقاعد).
- تسجيل الطلاب في الدورات والتحقق من توفر المقاعد قبل إتمام التسجيل.
- منع تكرار تسجيل نفس الطالب في الدورة نفسها.
- تقليل عدد المقاعد المتاحة تلقائيًا بعد كل تسجيل ناجح.
- عرض عدد الطلاب المسجلين في كل دورة.
- تنظيم العلاقات بين الجداول بطريقة واضحة (الدورة ↔ التسجيل ↔ الطالب).

🔹 **In English:**  
The system provides the following functionalities:
- Create and manage training course details (name, trainer, date, available seats).
- Register students with real-time seat availability validation.
- Prevent duplicate registrations for the same course.
- Auto-decrease available seats upon successful enrollment.
- Display number of enrolled students in each course.
- Maintain clean relationships between tables (Course ↔ Enrollment ↔ Student).

---

## 🎯 الهدف من المشروع | Project Objective

🔹 **بالعربية:**  
بناء نظام سهل الاستخدام وفعّال يساعد على تنظيم عمليات التدريب، مع ضمان دقة البيانات ومنع التكرار وتحقيق تجربة استخدام سلسة.

🔹 **In English:**  
To build a reliable and user-friendly system that streamlines training operations, ensures data integrity, prevents duplication, and delivers a smooth user experience.

---

## 👤 المطور | Developed By

**حنان  الجابر | Hanan  Aljaber**  
طالبة في تخصص علوم الحاسب - التدريب التعاوني (CAS400)  
Intern at **Helcon IT Company (TeleNoc)** - Odoo ERP Department


# Training Course Registration Management System

This project is a custom Odoo module developed to manage the registration of students in training courses.

## 📌 Project Description

The system allows administrators to:

- Create and manage training courses (name, trainer, date, available seats).
- Register students in courses with seat availability checks.
- Prevent duplicate registration of a student in the same course.
- Automatically reduce available seats after registration.
- Show how many students are enrolled in each course.
- Maintain clean relations between courses, students, and enrollments.

## 📂 Module Structure

- `training_management/` — Main custom module directory.
  - Models
  - Views
  - Security
  - Menus
  - Workflows

## 💡 Objective

To build a reliable and user-friendly module that streamlines training course registration and ensures data integrity.

---

Developed by **Hanan Aljaber**  
Supervised during Cooperative Training (CAS400)
