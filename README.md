# ROS1 Noitec & ROS2 Foxy installation 
فالبداية لتثبيت برنامج ROS1 نسخة Foxy يتطلب البرنامج نظام تشغيل Linux.

يمكن محاكاة أنظمة التشغيل المختلفة عن طريق تحميل تحميل منصة افتراضية داخل الجهاز( Virtual Work Station).

في هذا المشروع تم تحميل VirtualBox من الرابط التالي:
https://www.virtualbox.org/wiki/Downloads 
لتثبيت أحدث نسخة سوف يتطلب تحميل حزم إضافية على هذا الرابط:
https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022

بعدها يتم تثبيت نسخة نظام التشغيل المطلوبة، فيها المثال سيتم استخدام نسخة UBUNTU 20.04 TLS.
متوفر للتحميل على الرابط التالي: https://releases.ubuntu.com/20.04/ 

بعد أن يتم تحميل نسخة نظام التشغيل يتم تشغيل المنصة الافتراضية بنظام التشغيل المطلوب.
يتم تثبيت ROS1 بفتح الterminal في نظام تشغيل Linux وإدخال الأوامر التالية على الرابط التالي: http://wiki.ros.org/ROS/Installation 

بعد الانتهاء من التثبيت يمكن استدعاء البرنامج عن طريق كتابة الكود: 
$ roscore

لتظهر لك الصورة التالية:
![image](https://github.com/user-attachments/assets/298b9fe0-fdb7-4a8e-8044-18ada46998a0)

بعدها يتم تثبيت ROS2 نسخة Foxy عن طريق الرابط التالي:
https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html

بعد التثيست يمكن اختبار البرنامج عن طريق استخدام الكود التالي:
source /opt/ros/foxy/setup.bash

ros2 run demo_nodes_cpp talker

ثم استخدام الكود التالي في صفحة أخرى:
source /opt/ros/foxy/setup.bash

ros2 run demo_nodes_py listener

لتظهر لك صفحة بهذا الشكل:
![image](https://github.com/user-attachments/assets/7902057a-c8b0-4cf1-b211-46e7f5fd6d91)


