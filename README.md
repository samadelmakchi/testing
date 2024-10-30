# Testing
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  -->

### Functional Testing vs Non-Functional Testing
Below are the differences between functional testing and non-functional testing:
|Parameters                      |Functional Testing	                                                   |Non-functional Testing                                                       |
|--------------------------------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------|
|Definition                      |Functional testing verifies the operations and actions of an application |Non-functional verifies the behavior of an application                       |
|Testing based on	             |It is based on the requirements of the customer                          |It is based on the expectations of the customer                              |
|Objective                       |The objective is to validate software actions	                           |The objective is to performance of the software system                       |
|Requirements                    |Functional testing is carried out using the functional specification     |Non-functional testing is carried out using the performance specifications   |
|Functionality                   |It describes what the product does	                                   |It describes how the product works                                           |

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  -->

### Type of Functional Testing Techniques
There are various types of functional testing which are as follows:

- **Unit Testing**
    Unit testing is the type of functional testing technique where the individual units or modules of the application are tested. It ensures that each module is working correctly.
    > *Tools : PyTest,PHPUnit*
    <!-- تست واحد معمولاً در هر پروژه‌ای اجرا می‌شود تا اطمینان حاصل شود که اجزای کوچکی از کد درست کار می‌کنند -->
- **Integration Testing**
    In Integration testing , combined individual units are tested as a group and expose the faults in the interaction between the integrated units.
    > *Tools : Apache Camel Test Kit, TestNG، JUnit*
    <!-- تست های یکپارچگی برای بررسی تعامل بین ماژول‌های مختلف به‌کار می‌روند -->
- **Smoke Testing**
    Smoke testing is a type of functional testing technique where the basic functionality or feature of the application is tested as it ensures that the most important function works properly.
    > *Tools : Cypress، Selenium*
    <!-- تست دودی که تست‌های سطحی برای بررسی سلامت کلی سیستم است -->
- **User Acceptance Testing**
    User acceptance testing is done by the client to certify that the system meets the requirements and works as intended. It is the final phase of testing before the product release.
    > *Tools : FitNesse, Cucumber، Robot Framework*
    <!-- تست نهایی توسط کاربر یا مشتری برای اطمینان از اینکه نرم‌افزار مطابق با نیازها است -->
- **Interface Testing**
    Interface testing is a type of software testing technique that checks the proper interaction between two different software systems.
    > *Tools : Selenium, Cypress، Puppeteer*
    <!-- این تست‌ها برای این تا اطمینان حاصل شود که رابط کاربری به‌درستی کار می‌کند -->
- **System Testing**
    System testing is a type of software testing that is performed on the complete integrated system to evaluate the compliance of the system with the corresponding requirements.
    > *Tools : Robot Framework*
    <!-- تست کل سیستم به عنوان یک واحد کامل پس از ادغام تمام ماژول‌ها -->
- **Regression Testing**
    Regression testing is done to make sure that the code changes do not affect the existing functionality and the features of the application. It concentrates on whether all parts are working or not.
    > *Tools : Selenium, Cypress*
    <!-- تست مجدد بخش‌هایی از نرم‌افزار برای اطمینان از اینکه تغییرات جدید باعث ایجاد باگ‌های جدید نشده است -->
- **White box Testing**
    White box testing is a type of software testing that allows the tester to verify the internal workings of the software system. This includes analyzing the code, infrastructure, and integrations with the external system.
    > *Tools : JUnit، TestNG*
    <!-- تست با دانستن ساختار داخلی کد و بررسی دقیق نحوه عملکرد داخلی نرم‌افزار -->
- **Black box Testing**
    Black box testing is a type of software testing where the functionality of the software system is tested without looking at the internal workings or structures of the software system.
    > *Tools : TestNG*
    <!-- تست بدون توجه به ساختار داخلی کد و با تمرکز بر عملکرد نرم‌افزار از دید کاربر -->
- **Recovery Testing**
    Recovery testing is a type of software testing that verifies the software’s ability to recover from failures like hardware failures, software failures, crashes, etc.
    > *Tools : Chaos Monkey*
    <!-- برای تست بازیابی سیستم‌ها -->
- **Sanity Testing**
    Sanity testing is a subset of regression testing and is done to make sure that the code changes introduced are working as expected.
    > *Tools :*
- **Database Testing**
    Database testing is a type of software testing that checks the schema, tables, etc of the database under test.
    > *Tools :*
- **Adhoc Testing**
    Adhoc testing also known as monkey testing or random testing is a type of software testing that does not follow any documentation or test plan to perform testing.
    > *Tools :*
- **Static Testing**
    Static testing is a type of software testing that is performed to check the defects in software without actually executing the code of the software application.
    > *Tools :*
- **Grey-box Testing**
    Grey box testing is a type of software testing that includes black-box and white-box testing.
    > *Tools :*
- **Component Testing**
    Component testing also known as program testing or module testing is a type of software testing that is done after the unit testing. In this, the test objects can be tested independently as a component without integrating with other components.
    > *Tools :*
- **Migration Test**
    > *Tools : Flyway*
    <!-- برای مهاجرت دیتابیس‌ها -->
- **API Test**
    > *Tools : RestAssured، SoapUI, Postman & Newman*
    <!-- تست میکروسرویس ها -->
- **Accessibility Test**
    > *Tools : axe-core*
    <!-- تست قابلیت دسترسی -->

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  -->

### Type of Non-Functional Testing Techniques
There are various types of non-functional testing which are as follows:

- **Compatibility testing**
    is a type of testing to ensure that a software program or system is compatible with other software programs or systems. For example, in this, the tester checks that the software is compatible with other software, operating systems, etc.
    > *Tools : Selenium, BrowserStack*
    <!-- برای تست سازگاری نرم‌افزار در مرورگرها و دستگاه‌های مختلف استفاده می شود -->
- **Endurance testing**
    is a type of testing to ensure that a software program or system can handle a long-term, continuous load. For example for the banking application, the application is tested to know if the system can sustain under the continuous expected load.
    > *Tools : Locust, Apache JMeter*
    <!-- این تست نشان می‌دهد که آیا سیستم تحت بارهای مداوم و طولانی به درستی عمل می‌کند یا خیر -->
- **Load testing**
    is a type of testing to ensure that a software program or system can handle a large number of users or transactions. For example, Running multiple applications on the computer simultaneously. 
    > *Tools : Locust, Apache JMeter*
    <!-- سیستم در چه مقدار بار به درستی عمل می‌کند -->
- **Performance testing**
    is a type of testing to ensure that a software program or system meets specific performance goals, such as response time or throughput. For example, organizations perform performance tests to identify performance-related bottlenecks.
    > *Tools : Locust, Apache JMeter، Gatling*
    <!-- بررسی سرعت، پاسخگویی و پایداری نرم‌افزار در شرایط مختلف -->
- **Security testing**
    is a type of testing to ensure that a software program or system is secure from unauthorized access or attack. For example, Organizations perform security testing to reveal flaws in the security mechanism of the information system.
    > *Tools : OWASP ZAP, Arachni*
    <!-- ابزارهای تست امنیتی می‌توانند برای بررسی آسیب‌پذیری‌های امنیتی استفاده شوند -->
- **Scalability testing**
    is a type of testing to ensure that a software program or system can be scaled up or down to meet changing needs. For example, to measure the application’s capability to scale up or scale out in terms of non-functional capability. 
    > *Tools : Locust, Apache JMeter*
    <!-- ارزیابی اینکه چگونه سیستم با افزایش تدریجی تعداد کاربران یا درخواست‌ها سازگار می‌شود، انجام می‌شود -->
- **Stress testing**
    is a type of testing to ensure that a software program or system can handle an unusually high load. For example, extremely large numbers of concurrent users try to log into the application.
    > *Tools : Locust, Apache JMeter*
    <!-- برای بررسی میزان تحمل سیستم در برابر بارهای سنگین و فراتر از ظرفیت معمول استفاده می‌شود. هدف این تست بررسی نقطه‌ی شکست سیستم است -->
- **Localization testing**
    is a type of software testing that is performed to verify the performance and quality of the software for a specific culture and to make the product look more natural for the foreign target audience.
    > *Tools : Globalyzer*
    <!-- تست جهانی‌سازی و بومی‌سازی -->
- **Reliability testing**
    is checks that the application can perform a failure-free operation for the specified period of time in the given environmental conditions.
    > *Tools : Chaos Monkey*
    <!-- تست قابلیت اطمینان -->
- **Compliance testing**
    is a type of testing to ensure that a software program or system meets a specific compliance standard, such as HIPAA or Sarbanes-Oxley. It is often the first type of testing that is performed when accessing the control environment.
    > *Tools :*
- **Usability testing**
    is a type of testing to ensure that a software program or system is easy to use. For example, on the e-commerce website, it can be tested whether the users can easily locate the Buy Now button or not.
    > *Tools :*
- **Volume testing**
    is a type of testing to ensure that a software program or system can handle a large volume of data. For example, if the website is developed to handle traffic of 500 users, volume testing will whether the site is able to handle 500 users or not.
    > *Tools :*
- **Failover testing**
    is validates the system’s capability to allocate sufficient resources toward recovery during a server failure.
    > *Tools :*
- **Portability testing**
    is testing the ease with which the application can be moved from one environment to another. 
    > *Tools :*
- **Baseline testing**
    is used to make sure that the application performance is not degraded over time with new changes. 
    > *Tools :*
- **Documentation testing**
    is a type of software testing that involves testing the documented artifacts developed before or during the software testing process.
    > *Tools :*
- **Internationalization testing**
    is a type of software testing that ensures the adaptability of software to different cultures and languages around the world accordingly without any modifications in source code.  
    > *Tools :*
