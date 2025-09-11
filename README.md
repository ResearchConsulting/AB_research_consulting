<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الباحثة أبرار المطيري | Researcher Abrar Almutairi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Tajawal', sans-serif;
            color: #333;
            scroll-behavior: smooth;
            background-color: #f0fdf4;
            background-image: radial-gradient(at 0% 100%, #ecfdf5, transparent), radial-gradient(at 100% 0%, #dbeafe, transparent);
            background-size: 100% 100%;
        }
        .text-gradient-teal {
            background-image: linear-gradient(to right, #10B981, #06B6D4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .bg-gradient-teal {
            background-image: linear-gradient(to bottom, #d1fae5, #a7f3d0);
        }
        .container-section {
            padding: 3rem 1.5rem;
        }
        .shadow-custom {
            box-shadow: 0 15px 35px -5px rgba(0, 0, 0, 0.1), 0 5px 15px -5px rgba(0, 0, 0, 0.05);
        }
        .glass-bg {
            background-color: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
        }
        .nav-link {
            transition: color 0.3s, transform 0.2s, background-color 0.3s;
            border-radius: 9999px;
            padding: 0.5rem 1rem;
        }
        .nav-link:hover {
            color: #06B6D4;
            transform: scale(1.05);
            background-color: #e5e7eb;
        }
        .lang-btn {
            transition: transform 0.2s, background-color 0.3s;
        }
        .lang-btn:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-blue-50">

    <!-- شريط التنقل العلوي (Header) -->
    <header class="relative overflow-hidden bg-white shadow-lg z-50">
        <div class="container mx-auto px-6 py-4 flex flex-col md:flex-row justify-between items-center">
            <!-- أزرار اللغة على اليمين -->
            <div class="z-50 flex items-center mb-4 md:mb-0 space-x-4 space-x-reverse md:order-2">
                <button id="lang-toggle-ar" class="lang-btn px-4 py-2 bg-teal-600 text-white rounded-full font-semibold hover:bg-teal-700 transition duration-300">
                    العربية
                </button>
                <button id="lang-toggle-en" class="lang-btn px-4 py-2 bg-gray-300 text-gray-800 rounded-full font-semibold hover:bg-gray-400 transition duration-300">
                    English
                </button>
            </div>
            
            <!-- روابط التنقل على اليسار -->
            <nav class="md:order-1">
                <ul class="flex flex-wrap justify-center md:justify-start gap-4 text-lg font-semibold text-gray-700">
                    <li><a href="#home" class="nav-link" data-lang-ar="الرئيسية" data-lang-en="Home">الرئيسية</a></li>
                    <li><a href="#about" class="nav-link" data-lang-ar="عني" data-lang-en="About Me">عني</a></li>
                    <li><a href="#feedback" class="nav-link" data-lang-ar="ملاحظات" data-lang-en="Feedback">ملاحظات</a></li>
                    <li><a href="#consultation" class="nav-link" data-lang-ar="حجز استشارة" data-lang-en="Book a Consultation">حجز استشارة</a></li>
                    <li><a href="#contact" class="nav-link" data-lang-ar="بيانات التواصل" data-lang-en="Contact Details">بيانات التواصل</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container mx-auto mt-16 px-4 md:px-6">

        <!-- قسم البداية (Hero) -->
        <section id="home" class="container-section text-center mb-16">
            <h1 class="text-5xl md:text-6xl font-extrabold mb-4 leading-tight text-gray-900" data-lang-ar="الباحثة أبرار المطيري" data-lang-en="Researcher Abrar Almutairi">
                <span class="text-gradient-teal" data-lang-ar="الباحثة أبرار المطيري" data-lang-en="Researcher Abrar Almutairi">الباحثة أبرار المطيري</span>
            </h1>
            <p class="text-lg md:text-xl text-gray-700" data-lang-ar="خبير في مجال الصحة العامة والبحث العلمي" data-lang-en="Expert in Public Health and Scientific Research">
                خبير في مجال الصحة العامة والبحث العلمي
            </p>
        </section>

        <!-- قسم عني (About) -->
        <section id="about" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="عني" data-lang-en="About Me">
                    <span class="text-gradient-teal">عني</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="تعرف على مسيرتي المهنية وخبراتي" data-lang-en="Learn about my professional journey and expertise">
                    تعرف على مسيرتي المهنية وخبراتي
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner">
                <p class="text-lg text-gray-700 mb-6 leading-relaxed" data-lang-ar="أبرار المطيري باحثة متخصصة في مجال الصحة العامة، حاصلة على درجة الماجستير من جامعة غلاسكو كاليدونيان. تتمتع بتركيز أكاديمي قوي على منهجية البحث والإحصاء الحيوي، مما أهلها لتكون خبيرة في هذا المجال. بدأت مسيرتها المهنية في مركز الملك عبد الله العالمي للأبحاث الطبية (KAIMRC) ضمن قسم صحة السكان، حيث اكتسبت خبرة واسعة في إجراء الأبحاث والتحليل الإحصائي." data-lang-en="Abrar Almutairi is a specialized researcher in Public Health, holding a Master's degree from Glasgow Caledonian University. She has a strong academic focus on research methodology and biostatistics, which has qualified her as an expert in this field. She began her professional career at King Abdullah International Medical Research Center (KAIMRC) within the Population Health Department, where she gained extensive experience in conducting research and statistical analysis.">
                    أبرار المطيري باحثة متخصصة في مجال الصحة العامة، حاصلة على درجة الماجستير من جامعة غلاسكو كاليدونيان. تتمتع بتركيز أكاديمي قوي على منهجية البحث والإحصاء الحيوي، مما أهلها لتكون خبيرة في هذا المجال. بدأت مسيرتها المهنية في مركز الملك عبد الله العالمي للأبحاث الطبية (KAIMRC) ضمن قسم صحة السكان، حيث اكتسبت خبرة واسعة في إجراء الأبحاث والتحليل الإحصائي.
                </p>
                <p class="text-lg text-gray-700 mb-6 leading-relaxed" data-lang-ar="تعمل حاليًا في قسم الأبحاث بجامعة الملك سعود بن عبد العزيز للعلوم الصحية (KSAU-HS)، حيث تقدم دعمًا مهنيًا للطلاب والأكاديميين والمتخصصين في مختلف جوانب البحث العلمي. وتساهم في نشر المعرفة من خلال تنظيم ورش العمل والمحاضرات، وتقديم الدعم في كافة مراحل دورة البحث، من الفكرة الأولية حتى النشر النهائي." data-lang-en="She currently works in the Research Department at King Saud bin Abdulaziz University for Health Sciences (KSAU-HS), where she provides professional support to students, academics, and professionals in various aspects of scientific research. She contributes to knowledge dissemination by organizing workshops and lectures, and providing support throughout all stages of the research cycle, from the initial idea to final publication.">
                    تعمل حاليًا في قسم الأبحاث بجامعة الملك سعود بن عبد العزيز للعلوم الصحية (KSAU-HS)، حيث تقدم دعمًا مهنيًا للطلاب والأكاديميين والمتخصصين في مختلف جوانب البحث العلمي. وتساهم في نشر المعرفة من خلال تنظيم ورش العمل والمحاضرات، وتقديم الدعم في كافة مراحل دورة البحث، من الفكرة الأولية حتى النشر النهائي.
                </p>
                <p class="text-lg text-gray-700 leading-relaxed" data-lang-ar="ساهمت في نشر أكثر من 10 أوراق بحثية، منها منشورين كمؤلف أول في مجلات مرموقة ذات تأثير عالٍ. كما قدمت أكثر من 200 استشارة بحثية متخصصة. هذه الخبرة الواسعة مكنتها من العمل كمراجع علمي للعديد من المجلات الدولية المرموقة، وكمراجع في مؤتمرات صحية وهاكاثونات على المستوى الوطني في المملكة العربية السعودية." data-lang-en="She has contributed to publishing over 10 research papers, including two as a first author in high-impact journals. She has also provided more than 200 specialized research consultations. This extensive experience has enabled her to serve as a scientific reviewer for several prestigious international journals, as well as a reviewer at national health conferences and hackathons in Saudi Arabia.">
                    ساهمت في نشر أكثر من 10 أوراق بحثية، منها منشورين كمؤلف أول في مجلات مرموقة ذات تأثير عالٍ. كما قدمت أكثر من 200 استشارة بحثية متخصصة. هذه الخبرة الواسعة مكنتها من العمل كمراجع علمي للعديد من المجلات الدولية المرموقة، وكمراجع في مؤتمرات صحية وهاكاثونات على المستوى الوطني في المملكة العربية السعودية.
                </p>
            </div>
        </section>

        <!-- قسم المسيرة المهنية (Professional Journey) -->
        <section id="professional-journey" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="المسيرة المهنية" data-lang-en="Professional Journey">
                    <span class="text-gradient-teal">المسيرة المهنية</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="نظرة على أهم المحطات في مسيرتي المهنية" data-lang-en="A look at the key milestones in my professional career">
                    نظرة على أهم المحطات في مسيرتي المهنية
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner space-y-8">
                <div>
                    <h3 class="font-bold text-2xl text-teal-800 mb-2" data-lang-ar="مساعد باحث "data-lang-en="Research Assistant">مساعد باحث "مشرف"</h3>
                    <p class="text-gray-600 font-medium mb-2" data-lang-ar="جامعة الملك سعود بن عبدالعزيز للعلوم الصحية، الرياض، أبريل 2022 - حتى الآن" data-lang-en="King Saud bin Abdulaziz University for Health Sciences, Riyadh, Apr 2022-Present">جامعة الملك سعود بن عبدالعزيز للعلوم الصحية، الرياض، أبريل 2022 - حتى الآن</p>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li data-lang-ar="الإشراف ودعم خدمات التحليل الإحصائي للباحثين والطلاب." data-lang-en="Supervising and supporting statistical analysis services for researchers and students.">الإشراف ودعم خدمات التحليل الإحصائي للباحثين والطلاب.</li>
                        <li data-lang-ar="العمل كمراجع علمي للمخطوطات البحثية." data-lang-en="Serving as a scientific reviewer for research manuscripts.">العمل كمراجع علمي للمخطوطات البحثية.</li>
                        <li data-lang-ar="مدير مشروع للمبادرات البحثية، بما في ذلك 'المشاريع الضخمة'." data-lang-en="Project manager for research initiatives, including 'Mega Projects.'">مدير مشروع للمبادرات البحثية، بما في ذلك 'المشاريع الضخمة'.</li>
                        <li data-lang-ar="تقديم استشارات بحثية شاملة، بما في ذلك إعداد المخطوطات، والتحليل الإحصائي، وإدارة البيانات، وتنظيم المراجع، ومراجعة المخطوطات." data-lang-en="Providing comprehensive research consultations, including manuscript preparation, statistical analysis, data management, and manuscript review.">تقديم استشارات بحثية شاملة، بما في ذلك إعداد المخطوطات، والتحليل الإحصائي، وإدارة البيانات، وتنظيم المراجع، ومراجعة المخطوطات.</li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-2xl text-teal-800 mb-2" data-lang-ar="مستشار بحث بدوام جزئي" data-lang-en="Part-Time Research Consultant">مستشار بحث بدوام جزئي</h3>
                    <p class="text-gray-600 font-medium mb-2" data-lang-ar="جامعة الأميرة نورة بنت عبدالرحمن (PNU)، الرياض، ديسمبر 2023 - مايو 2024" data-lang-en="Princess Nourah Bint Abdulrahman University (PNU), Riyadh, December 2023 - May 2024">جامعة الأميرة نورة بنت عبدالرحمن (PNU)، الرياض، ديسمبر 2023 - مايو 2024</p>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li data-lang-ar="تقديم خدمات التحليل الإحصائي لأعضاء هيئة التدريس والباحثين الطلاب." data-lang-en="Provided statistical analysis services to faculty and student researchers.">تقديم خدمات التحليل الإحصائي لأعضاء هيئة التدريس والباحثين الطلاب.</li>
                        <li data-lang-ar="الإشراف على الطلاب المتدربين خلال مشاريعهم البحثية، وتقديم الإرشاد في المنهجية والتحليل." data-lang-en="Supervised intern students throughout their research projects, offering guidance in methodology and analysis.">الإشراف على الطلاب المتدربين خلال مشاريعهم البحثية، وتقديم الإرشاد في المنهجية والتحليل.</li>
                        <li data-lang-ar="تقديم ورش عمل ومحاضرات حول دورة البحث، تغطي المراحل الرئيسية من التخطيط إلى النشر." data-lang-en="Delivered workshops and lectures on the research cycle, covering key phases from planning to publication.">تقديم ورش عمل ومحاضرات حول دورة البحث، تغطي المراحل الرئيسية من التخطيط إلى النشر.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- قسم المنشورات والتقييم العلمي (Publications and Scientific Review) -->
        <section id="publications-review" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="المنشورات والتقييم العلمي" data-lang-en="Publications & Scientific Review">
                    <span class="text-gradient-teal">المنشورات والتقييم العلمي</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="أبرز الأوراق البحثية والمساهمات العلمية" data-lang-en="Key research papers and scientific contributions">
                    أبرز الأوراق البحثية والمساهمات العلمية
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner space-y-8">
                <div>
                    <h3 class="font-bold text-2xl text-teal-800 mb-2" data-lang-ar="منشورات مختارة" data-lang-en="Selected Publications">منشورات مختارة</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li data-lang-ar="مؤلف أول في مجلة Frontiers in Endocrinology" data-lang-en="First-author publication in the journal Frontiers in Endocrinology">مؤلف أول في مجلة Frontiers in Endocrinology</li>
                        <li data-lang-ar="مؤلف أول في مجلة Burns Open" data-lang-en="First-author publication in the journal Burns Open">مؤلف أول في مجلة Burns Open</li>
                        <li data-lang-ar="المساهمة في أكثر من 10 أوراق بحثية منشورة في مجلات دولية." data-lang-en="Contributing to more than 10 research papers published in international journals.">المساهمة في أكثر من 10 أوراق بحثية منشورة في مجلات دولية.</li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-2xl text-teal-800 mb-2" data-lang-ar="أدوار التقييم العلمي" data-lang-en="Scientific Review Roles">أدوار التقييم العلمي</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li data-lang-ar="مراجع علمي لمجلة Diabetes, Metabolic Syndrome and Obesity" data-lang-en="Peer Reviewer for the Diabetes, Metabolic Syndrome and Obesity">مراجع علمي لمجلة Diabetes, Metabolic Syndrome and Obesity</li>
                        <li data-lang-ar="مراجع علمي لمجلة BMC Public Health (Springer Nature)" data-lang-en="Peer Reviewer for the BMC Public Health (Springer Nature)">مراجع علمي لمجلة BMC Public Health (Springer Nature)</li>
                        <li data-lang-ar="مراجع في المؤتمر الوطني للمهن الصحية في المملكة العربية السعودية." data-lang-en="Reviewer at the National Health Conference in Saudi Arabia.">مراجع في المؤتمر الوطني للمهن الصحية في المملكة العربية السعودية.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- قسم المؤتمرات والورش (Conferences and Workshops) -->
        <section id="conferences-workshops" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="المؤتمرات والورش" data-lang-en="Conferences & Workshops">
                    <span class="text-gradient-teal">المؤتمرات والورش</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="مشاركاتي كمتحدث وعضو في اللجان" data-lang-en="My participations as a speaker and committee member">
                    مشاركاتي كمتحدث وعضو في اللجان
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner space-y-8">
                <div>
                    <h3 class="font-bold text-2xl text-teal-800 mb-2" data-lang-ar="أدوار قيادية وعضوية لجان" data-lang-en="Leadership Roles & Committee Memberships">أدوار قيادية وعضوية لجان</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li data-lang-ar="مؤسس نادي البحث العلمي في كلية العلوم الصحية التطبيقية، KSAU-HS." data-lang-en="Founder of the Research Club at the College of Applied Medical Sciences, KSAU-HS.">مؤسس نادي البحث العلمي في كلية العلوم الصحية التطبيقية، KSAU-HS.</li>
                        <li data-lang-ar="مدير ومقدم في يوم البحث والابتكار الرابع." data-lang-en="Manager and presenter at the 4th Research and Innovation Day.">مدير ومقدم في يوم البحث والابتكار الرابع.</li>
                        <li data-lang-ar="عضو لجنة تقييم الأبحاث في مؤتمر المهن الصحية." data-lang-en="Member of the Research Evaluation Committee at the Health Professions Conference.">عضو لجنة تقييم الأبحاث في مؤتمر المهن الصحية.</li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-2xl text-teal-800 mb-2" data-lang-ar="ورش عمل ومحاضرات" data-lang-en="Workshops & Lectures">ورش عمل ومحاضرات</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li data-lang-ar="متحدث في " data-lang-en="Speaker at ">متحدث في "How to Write an Abstract in Research" و "Data Cleaning and Management".</li>
                        <li data-lang-ar="متحدث في مؤتمر المهن الصحية الثامن بـ KSAU-HS." data-lang-en="Speaker at the 8th Health Professions Conference at KSAU-HS.">متحدث في مؤتمر المهن الصحية الثامن بـ KSAU-HS.</li>
                        <li data-lang-ar="متدرب في ورشة عمل بناء القدرات البحثية للمرأة في بداية مسيرتها المهنية." data-lang-en="Trainee in the Early Career Women in Research Capacity Building Workshop.">متدرب في ورشة عمل بناء القدرات البحثية للمرأة في بداية مسيرتها المهنية.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- قسم الخدمات (Services) -->
        <section id="services" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="خدمات البحث" data-lang-en="Research Services">
                    <span class="text-gradient-teal">خدمات البحث</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="خدمات استشارية وتحليلية عالية الجودة" data-lang-en="High-quality consultancy and analytical services">
                    خدمات استشارية وتحليلية عالية الجودة
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner">
                <p class="text-lg text-gray-700 mb-8 leading-relaxed" data-lang-ar="تقدم أبرار خدمات استشارية وتحليل إحصائي عالية الجودة للطلاب والأكاديميين والمهنيين. نحن نقدم دعمًا متخصصًا في:" data-lang-en="Abrar offers high-quality research consultation and statistical analysis services for students, academics, and professionals. We provide expert support in:">
                    تقدم أبرار خدمات استشارية وتحليل إحصائي عالية الجودة للطلاب والأكاديميين والمهنيين. نحن نقدم دعمًا متخصصًا في:
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-2xl shadow-md hover:shadow-lg transition-shadow duration-300 transform hover:scale-105">
                        <h3 class="font-bold text-xl text-teal-800 mb-2" data-lang-ar="استشارات البحث" data-lang-en="Research Consultation">استشارات البحث</h3>
                        <p class="text-gray-700" data-lang-ar="توجيه شامل في جميع مراحل البحث العلمي." data-lang-en="Comprehensive guidance throughout all stages of scientific research.">توجيه شامل في جميع مراحل البحث العلمي.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-md hover:shadow-lg transition-shadow duration-300 transform hover:scale-105">
                        <h3 class="font-bold text-xl text-teal-800 mb-2" data-lang-ar="التحليل الإحصائي" data-lang-en="Statistical Analysis">التحليل الإحصائي</h3>
                        <p class="text-gray-700" data-lang-ar="تحليل دقيق للبيانات باستخدام أحدث الأساليب الإحصائية." data-lang-en="Accurate data analysis using the latest statistical methods.">تحليل دقيق للبيانات باستخدام أحدث الأساليب الإحصائية.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-md hover:shadow-lg transition-shadow duration-300 transform hover:scale-105">
                        <h3 class="font-bold text-xl text-teal-800 mb-2" data-lang-ar="المراجعة المنهجية" data-lang-en="Systematic Review">المراجعة المنهجية</h3>
                        <p class="text-gray-700" data-lang-ar="دعم متخصص في إعداد المراجعات المنهجية." data-lang-en="Specialized support in preparing systematic reviews.">دعم متخصص في إعداد المراجعات المنهجية.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-md hover:shadow-lg transition-shadow duration-300 transform hover:scale-105">
                        <h3 class="font-bold text-xl text-teal-800 mb-2" data-lang-ar="دعم كتابة الأبحاث" data-lang-en="Research Writing Support">دعم كتابة الأبحاث</h3>
                        <p class="text-gray-700" data-lang-ar="مساعدة في صياغة وكتابة الأوراق البحثية." data-lang-en="Assistance in drafting and writing research papers.">مساعدة في صياغة وكتابة الأوراق البحثية.</p>
                    </div>
                    <div class="bg-white p-6 rounded-2xl shadow-md hover:shadow-lg transition-shadow duration-300 transform hover:scale-105">
                        <h3 class="font-bold text-xl text-teal-800 mb-2" data-lang-ar="تدريب على دورة البحث" data-lang-en="Research Cycle Coach">تدريب على دورة البحث</h3>
                        <p class="text-gray-700" data-lang-ar="إرشاد وتدريب على جميع خطوات دورة البحث العلمي." data-lang-en="Guidance and training on all steps of the scientific research cycle.">إرشاد وتدريب على جميع خطوات دورة البحث العلمي.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- قسم الشهادات والمنشورات (Certificates and Publications) -->
        <section id="certificates" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="الشهادات والمنشورات" data-lang-en="Certificates and Publications">
                    <span class="text-gradient-teal">الشهادات والمنشورات</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="نظرة على أهم الإنجازات المهنية" data-lang-en="A look at the most important professional achievements">
                    نظرة على أهم الإنجازات المهنية
                </p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Certificate 1: Reviewer Certificate 2023 -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 1.49.53 PM (2).jpeg-5edb89b0-c2cc-4e01-81df-2bafc176ef4d" alt="Reviewer Certificate 2023" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="شهادة مراجع - 2023" data-lang-en="Reviewer Certificate - 2023">شهادة مراجع - 2023</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="مجلة Diabetes, Metabolic Syndrome and Obesity" data-lang-en="Journal of Diabetes, Metabolic Syndrome and Obesity">مجلة Diabetes, Metabolic Syndrome and Obesity</p>
                </div>
                <!-- Certificate 2: Reviewer Certificate Springer Nature -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 1.49.53 PM (1).jpeg-e81ba90b-2f28-481d-8431-68650f2a61e8" alt="Reviewer Certificate Springer Nature" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="شهادة مراجع - Springer Nature" data-lang-en="Reviewer Certificate - Springer Nature">شهادة مراجع - Springer Nature</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="مجلة BMC Public Health" data-lang-en="Journal of BMC Public Health">مجلة BMC Public Health</p>
                </div>
                <!-- Certificate 3: KSAU-HS Certificate of Appreciation -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 1.49.53 PM (3).jpeg-b964e1fd-ffd0-4e84-ba0d-4903728f5cbc" alt="KSAU-HS Certificate of Appreciation" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="شهادة تقدير - KSAU-HS" data-lang-en="Certificate of Appreciation - KSAU-HS">شهادة تقدير - KSAU-HS</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="لورشة عمل Mendeley" data-lang-en="for Mendeley Workshop">لورشة عمل Mendeley</p>
                </div>
                <!-- Certificate 4: KSAU-HS Research Club -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 1.49.53 PM (4).jpeg-460c5089-e3b1-4e03-b732-269fc40c6b33" alt="KSAU-HS Research Club" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="شهادة تأسيس - نادي البحث العلمي" data-lang-en="Founder Certificate - Research Club">شهادة تأسيس - نادي البحث العلمي</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="بجامعة الملك سعود للعلوم الصحية" data-lang-en="King Saud bin Abdulaziz University for Health Sciences">بجامعة الملك سعود للعلوم الصحية</p>
                </div>
                 <!-- Certificate 5: KAIMRC Research Summer School -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 1.49.53 PM (6).jpeg-8163e129-829e-4fb6-a35c-377872ad5e18" alt="KAIMRC Research Summer School" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="شهادة تقدير - مدرسة البحث الصيفية" data-lang-en="Certificate of Appreciation - Research Summer School">شهادة تقدير - مدرسة البحث الصيفية</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="كمتخصصة في علم الأوبئة" data-lang-en="as an Epidemiologist">كمتخصصة في علم الأوبئة</p>
                </div>
                <!-- Publication 1: Frontiers in Endocrinology -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 2.11.49 PM.jpeg-77718f5a-f585-4b7b-aafe-d4e863de25ea" alt="Frontiers in Endocrinology Publication" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="منشور بحثي - Frontiers in Endocrinology" data-lang-en="Research Publication - Frontiers in Endocrinology">منشور بحثي - Frontiers in Endocrinology</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="دراسة عن تأثير التطبيب عن بعد" data-lang-en="A study on the impact of telemedicine">دراسة عن تأثير التطبيب عن بعد</p>
                </div>
                <!-- Publication 2: Burns Open -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 2.12.31 PM.jpeg-cf73fa45-c105-4e5f-bca0-31c99e317f65" alt="Burns Open Publication" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="منشور بحثي - Burns Open" data-lang-en="Research Publication - Burns Open">منشور بحثي - Burns Open</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="دراسة عن حروق الأطفال والبالغين" data-lang-en="A study on burns in children and adults">دراسة عن حروق الأطفال والبالغين</p>
                </div>
                <!-- Certificate 6: KSAU-HS 8th Health Professions Conference -->
                <div class="bg-white p-4 rounded-2xl shadow-lg flex flex-col items-center hover:shadow-xl transition-shadow duration-300">
                    <img src="uploaded:WhatsApp Image 2025-09-11 at 1.49.53 PM (5).jpeg-0ec8a1f7-4957-4630-9842-95cdcdc8939c" alt="KSAU-HS 8th Health Professions Conference" class="w-full h-auto rounded-xl object-contain mb-4 border border-gray-200">
                    <h3 class="font-bold text-lg text-gray-800 text-center" data-lang-ar="درع تكريم - مؤتمر المهن الصحية الثامن" data-lang-en="Award of Appreciation - 8th Health Professions Conference">درع تكريم - مؤتمر المهن الصحية الثامن</h3>
                    <p class="text-sm text-gray-500 text-center" data-lang-ar="تكريم على المساهمات القيمة" data-lang-en="Honoring for valuable contributions">تكريم على المساهمات القيمة</p>
                </div>
            </div>
        </section>

        <!-- قسم الملاحظات (Feedback) -->
        <section id="feedback" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="قدم ملاحظاتك" data-lang-en="Provide Your Feedback">
                    <span class="text-gradient-teal">قدم ملاحظاتك</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="ملاحظاتكم تساعدنا على التحسين المستمر" data-lang-en="Your feedback helps us improve continuously">
                    ملاحظاتكم تساعدنا على التحسين المستمر
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner">
                <form action="https://docs.google.com/forms/d/e/1FAIpQLSfhya2O2A-ohLSySxvvd3E4ezgMgFcm4PfPM4S4nBt50VcPAQ/formResponse" method="POST" target="_blank" class="space-y-6">
                    <div>
                        <label for="name" class="block text-gray-700 font-medium mb-2" data-lang-ar="الاسم:" data-lang-en="Name:">الاسم:</label>
                        <input type="text" id="name" name="entry.1449079549" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="اسمك الكريم" data-lang-en-placeholder="Your full name" placeholder="اسمك الكريم" required>
                    </div>
                    <div>
                        <label for="email" class="block text-gray-700 font-medium mb-2" data-lang-ar="البريد الإلكتروني:" data-lang-en="Email:">البريد الإلكتروني:</label>
                        <input type="email" id="email" name="entry.1340157077" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="بريدك الإلكتروني" data-lang-en-placeholder="Your email" placeholder="بريدك الإلكتروني" required>
                    </div>
                    <div>
                        <label for="feedback" class="block text-gray-700 font-medium mb-2" data-lang-ar="ملاحظاتك:" data-lang-en="Your Feedback:">ملاحظاتك:</label>
                        <textarea id="feedback" name="entry.1691238917" rows="5" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="ملاحظاتك هنا..." data-lang-en-placeholder="Your feedback here..." placeholder="ملاحظاتك هنا..." required></textarea>
                    </div>
                    <button type="submit" class="w-full py-3 bg-teal-600 text-white font-semibold rounded-lg hover:bg-teal-700 transition duration-300 transform hover:scale-105 shadow-md" data-lang-ar="إرسال الملاحظات" data-lang-en="Submit Feedback">
                        إرسال الملاحظات
                    </button>
                </form>
            </div>
        </section>

        <!-- قسم حجز استشارة (Consultation) -->
        <section id="consultation" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="حجز استشارة" data-lang-en="Book a Consultation">
                    <span class="text-gradient-teal">حجز استشارة</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="املأ النموذج التالي لحجز موعد استشارة" data-lang-en="Fill out the form below to book a consultation appointment">
                    املأ النموذج التالي لحجز موعد استشارة
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner">
                <form class="space-y-6">
                    <div>
                        <label for="consultation-name" class="block text-gray-700 font-medium mb-2" data-lang-ar="الاسم الكامل:" data-lang-en="Full Name:">الاسم الكامل:</label>
                        <input type="text" id="consultation-name" name="consultation-name" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="اسمك الكامل" data-lang-en-placeholder="Your full name" required>
                    </div>
                    <div>
                        <label for="consultation-email" class="block text-gray-700 font-medium mb-2" data-lang-ar="البريد الإلكتروني:" data-lang-en="Email:">البريد الإلكتروني:</label>
                        <input type="email" id="consultation-email" name="consultation-email" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="بريدك الإلكتروني" data-lang-en-placeholder="Your email" required>
                    </div>
                    <div>
                        <label for="consultation-phone" class="block text-gray-700 font-medium mb-2" data-lang-ar="رقم الهاتف:" data-lang-en="Phone Number:">رقم الهاتف:</label>
                        <input type="tel" id="consultation-phone" name="consultation-phone" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="رقم هاتفك" data-lang-en-placeholder="Your phone number">
                    </div>
                    <div>
                        <label for="consultation-service" class="block text-gray-700 font-medium mb-2" data-lang-ar="الخدمة المطلوبة:" data-lang-en="Requested Service:">الخدمة المطلوبة:</label>
                        <select id="consultation-service" name="consultation-service" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" required>
                            <option value="" data-lang-ar="اختر خدمة..." data-lang-en="Select a service...">اختر خدمة...</option>
                            <option value="research-consultation" data-lang-ar="استشارات البحث" data-lang-en="Research Consultation">استشارات البحث</option>
                            <option value="statistical-analysis" data-lang-ar="التحليل الإحصائي" data-lang-en="Statistical Analysis">التحليل الإحصائي</option>
                            <option value="systematic-review" data-lang-ar="المراجعة المنهجية" data-lang-en="Systematic Review">المراجعة المنهجية</option>
                            <option value="research-writing-support" data-lang-ar="دعم كتابة الأبحاث" data-lang-en="Research Writing Support">دعم كتابة الأبحاث</option>
                            <option value="research-cycle-coach" data-lang-ar="تدريب على دورة البحث" data-lang-en="Research Cycle Coach">تدريب على دورة البحث</option>
                        </select>
                    </div>
                    <div>
                        <label for="consultation-message" class="block text-gray-700 font-medium mb-2" data-lang-ar="رسالتك (اختياري):" data-lang-en="Your Message (Optional):">رسالتك (اختياري):</label>
                        <textarea id="consultation-message" name="consultation-message" rows="5" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:border-teal-500 transition-colors" data-lang-ar-placeholder="أضف تفاصيل إضافية عن طلبك" data-lang-en-placeholder="Add additional details about your request"></textarea>
                    </div>
                    <button type="submit" class="w-full py-3 bg-teal-600 text-white font-semibold rounded-lg hover:bg-teal-700 transition duration-300 transform hover:scale-105 shadow-md" data-lang-ar="إرسال الطلب" data-lang-en="Submit Request">
                        إرسال الطلب
                    </button>
                </form>
            </div>
        </section>

        <!-- قسم بيانات التواصل (Contact Details) -->
        <section id="contact" class="container-section glass-bg rounded-3xl shadow-custom mb-16">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800" data-lang-ar="بيانات التواصل" data-lang-en="Contact Details">
                    <span class="text-gradient-teal">بيانات التواصل</span>
                </h2>
                <p class="text-gray-500 mt-2" data-lang-ar="تواصل معي مباشرة عبر القنوات التالية" data-lang-en="Contact me directly through the following channels">
                    تواصل معي مباشرة عبر القنوات التالية
                </p>
            </div>
            <div class="bg-white rounded-3xl p-8 shadow-inner space-y-6 text-center md:text-right">
                <div class="flex flex-col md:flex-row items-center justify-center md:justify-end space-y-2 md:space-y-0 md:space-x-4 md:space-x-reverse">
                    <span class="font-bold text-lg text-gray-800" data-lang-ar="البريد الإلكتروني:" data-lang-en="Email:">البريد الإلكتروني:</span>
                    <a href="mailto:Abrarmeshall@gmail.com" class="text-teal-600 hover:underline">Abrarmeshall@gmail.com</a>
                </div>
                <div class="flex flex-col md:flex-row items-center justify-center md:justify-end space-y-2 md:space-y-0 md:space-x-4 md:space-x-reverse">
                    <span class="font-bold text-lg text-gray-800" data-lang-ar="رقم الهاتف:" data-lang-en="Phone Number:">رقم الهاتف:</span>
                    <span class="text-gray-700">+966537182340</span>
                </div>
                <div class="flex flex-col md:flex-row items-center justify-center md:justify-end space-y-2 md:space-y-0 md:space-x-4 md:space-x-reverse">
                    <span class="font-bold text-lg text-gray-800" data-lang-ar="لينكدإن:" data-lang-en="LinkedIn:">لينكدإن:</span>
                    <a href="https://sa.linkedin.com/in/abrar-al-mutairi" target="_blank" class="text-teal-600 hover:underline">https://sa.linkedin.com/in/abrar-al-mutairi</a>
                </div>
            </div>
        </section>

    </main>

    <!-- تذييل الصفحة (Footer) -->
    <footer class="bg-gray-800 text-white py-8 mt-16">
        <div class="container mx-auto px-6 text-center">
            <p data-lang-ar="&copy; 2025 جميع الحقوق محفوظة للباحثة أبرار المطيري" data-lang-en="&copy; 2025 All rights reserved for Researcher Abrar Almutairi">&copy; 2025 جميع الحقوق محفوظة للباحثة أبرار المطيري</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const langToggleAr = document.getElementById('lang-toggle-ar');
            const langToggleEn = document.getElementById('lang-toggle-en');
            const htmlElement = document.documentElement;
            const navLinks = document.querySelectorAll('nav a');

            const switchLanguage = (lang) => {
                document.querySelectorAll('[data-lang-ar]').forEach(el => {
                    const arText = el.getAttribute('data-lang-ar');
                    const enText = el.getAttribute('data-lang-en');
                    el.textContent = (lang === 'en') ? enText : arText;
                });
                document.querySelectorAll('[data-lang-ar-placeholder]').forEach(el => {
                    const arPlaceholder = el.getAttribute('data-lang-ar-placeholder');
                    const enPlaceholder = el.getAttribute('data-lang-en-placeholder');
                    el.placeholder = (lang === 'en') ? enPlaceholder : arPlaceholder;
                });
                
                htmlElement.lang = lang;
                htmlElement.dir = (lang === 'ar') ? 'rtl' : 'ltr';

                const isArabic = (lang === 'ar');
                langToggleAr.classList.toggle('bg-teal-600', isArabic);
                langToggleAr.classList.toggle('text-white', isArabic);
                langToggleAr.classList.toggle('bg-gray-300', !isArabic);
                langToggleAr.classList.toggle('text-gray-800', !isArabic);

                langToggleEn.classList.toggle('bg-teal-600', !isArabic);
                langToggleEn.classList.toggle('text-white', !isArabic);
                langToggleEn.classList.toggle('bg-gray-300', isArabic);
                langToggleEn.classList.toggle('text-gray-800', isArabic);
            };

            navLinks.forEach(link => {
                link.addEventListener('click', (e) => {
                    e.preventDefault();
                    const targetId = link.getAttribute('href').substring(1);
                    const targetElement = document.getElementById(targetId);
                    if (targetElement) {
                        targetElement.scrollIntoView({ behavior: 'smooth' });
                    }
                });
            });

            langToggleAr.addEventListener('click', () => switchLanguage('ar'));
            langToggleEn.addEventListener('click', () => switchLanguage('en'));
            
            // Set initial language to Arabic
            switchLanguage('ar');
        });
    </script>
</body>
</html>
