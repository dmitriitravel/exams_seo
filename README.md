
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skysmart Exams: SEO-Стратегия и Продуктовые расчеты 2026</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght=300;400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #0f172a;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 320px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 380px;
            }
        }
        .funnel-step {
            transition: all 0.3s ease;
        }
        .funnel-step:hover {
            transform: scale(1.02);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }
        .custom-scroll::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        .custom-scroll::-webkit-scrollbar-track {
            background: #f1f5f9; 
            border-radius: 4px;
        }
        .custom-scroll::-webkit-scrollbar-thumb {
            background: #cbd5e1; 
            border-radius: 4px;
        }
        .custom-scroll::-webkit-scrollbar-thumb:hover {
            background: #94a3b8; 
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            900: '#1e3a8a',
                        },
                        accent: {
                            500: '#f59e0b',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="antialiased min-h-screen pb-12">

    <!-- Chosen Palette: Slate Backgrounds, Brand Blue (#3b82f6) and Amber (#f59e0b) accents. Clean, professional and highly legible. -->
    
    <!-- Application Structure Plan: Single-page application focused on the SEO & Product strategy of Skysmart Exams. Features include: 1. Strategic Intro, 2. Interactive Competitor Analysis Table focusing on Ambassador Strategy, 3. Interactive E-E-A-T landing page optimizer tabs, 4. Behavioral Funnel simulator for NavBoost, 5. Interactive Radar Comparison chart for E-E-A-T factors, 6. Dynamic Monthly Payments Chart based on precise CSV data with monthly/cumulative toggle, 7. Interactive Roadmap checklist with reactive progress tracker. No SVG/Mermaid used. All Javascript syntax errors are resolved. -->

    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->

    <header class="bg-white shadow-sm border-b border-slate-200 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <div>
                <h1 class="text-2xl font-bold text-slate-900 tracking-tight">Skysmart <span class="text-brand-600">Exams</span></h1>
                <p class="text-sm text-slate-500">SEO-Стратегия: Продвижение курсов ЕГЭ с амбассадорами</p>
            </div>
            <div class="hidden md:flex items-center space-x-2 bg-brand-50 px-4 py-2 rounded-full border border-brand-100">
                <span class="text-brand-600 text-lg">📈</span>
                <span class="text-sm font-medium text-brand-900">Продуктовая модель и планирование 2026-2027</span>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-8 space-y-8">
        
        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200">
            <div class="max-w-3xl">
                <h2 class="text-xl font-bold text-slate-800 mb-4">Вводная: Конкуренция на рынке EdTech (ЕГЭ)</h2>
                <p class="text-slate-600 mb-4 leading-relaxed">
                    Этот дашборд представляет план действий для масштабирования направления <strong>Exams</strong> (курсы подготовки к ЕГЭ от Skysmart с участием известных преподавателей-блогеров). Основные конкуренты в данном формате — <em>el-ed.ru</em>, <em>umschool.net</em> и <em>100points.ru</em>.
                </p>
                <p class="text-slate-600 leading-relaxed">
                    Стратегия направления Exams базируется на алгоритмическом прочтении параметров <strong>E-E-A-T</strong> (Опыт, Экспертиза, Авторитетность, Доверие) и оптимизации поведенческих факторов (NavBoost), чтобы поисковые системы распознавали страницы курсов с амбассадорами как наиболее релевантные и экспертные ответы на запросы школьников.
                </p>
            </div>
        </section>

        <!-- Исследование продуктовых решений конкурентов по стратегии амбассадоров -->
        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200 overflow-hidden">
            <div class="mb-6">
                <h2 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                    <span>🔄</span> Сравнение продуктовых решений конкурентов в стратегии амбассадоров
                </h2>
                <p class="text-sm text-slate-500 mt-2">
                    Детальный анализ продуктовых фич у Skysmart и лидирующих EdTech-проектов в сегменте подготовки к ЕГЭ через призму амбассадоров (преподавателей с личным брендом).
                </p>
            </div>
            <div class="overflow-x-auto custom-scroll border border-slate-100 rounded-xl">
                <table class="w-full text-left border-collapse text-sm min-w-[1000px]">
                    <thead>
                        <tr class="border-b border-slate-200 bg-slate-50">
                            <th class="p-4 font-semibold text-slate-700 w-1/5">Продуктовое решение (Пункт)</th>
                            <th class="p-4 font-semibold text-slate-700 w-1/5">Как это реализовано у Skysmart</th>
                            <th class="p-4 font-semibold text-slate-700 w-1/5">Умскул (umschool.net)</th>
                            <th class="p-4 font-semibold text-slate-700 w-1/5">ЕГЭЛЭНД (el-ed.ru)</th>
                            <th class="p-4 font-semibold text-slate-700 w-1/5">100балльный репетитор (100points.ru)</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-100">
                        <tr class="hover:bg-slate-50/50 transition-colors">
                            <td class="p-4 font-semibold text-slate-900">Персональное позиционирование амбассадоров и авторские бандлы</td>
                            <td class="p-4 text-slate-600">Курсы Exams встроены в общую сетку. На лендингах есть упоминания авторов, но отсутствует глубокая интеграция их личного медийного контента в воронку продаж.</td>
                            <td class="p-4 text-slate-600">Преподаватели выступают ключевыми медийными лицами. Каждый ведет личные TG и YouTube-каналы, глубоко интегрированные с платформой. Продажи идут через сильные личные бренды.</td>
                            <td class="p-4 text-slate-600">Маркетинг выстроен вокруг ярких образов преподавателей-блогеров. Лендинги курсов оформлены как презентационные страницы амбассадоров с их личным стилем, ценностями и эстетикой.</td>
                            <td class="p-4 text-slate-600">Бизнес-модель полностью построена вокруг топ-репетиторов (Эрик Ковалев, Саня Эбонит и др.). Каждый курс называется по имени амбассадора ("Легион", "Эбонит", "Биофак"). Ученик идет на конкретного человека.</td>
                        </tr>
                        <tr class="hover:bg-slate-50/50 transition-colors">
                            <td class="p-4 font-semibold text-slate-900">Интерактивный банк результатов выпускников</td>
                            <td class="p-4 text-slate-600">Отзывы представлены в виде статичных блоков с текстовыми цитатами без верификации и без прямых ссылок на профили выпускников в соцсетях.</td>
                            <td class="p-4 text-slate-600">Интерактивный раздел с базой результатов выпускников, где можно отфильтровать отзывы по предметам, баллам и годам, со ссылками на их ВК-профили для верификации абитуриентами.</td>
                            <td class="p-4 text-slate-600">Динамическая интерактивная витрина выпускников с видео-отзывами, фото реальных результатов ЕГЭ и интеграцией с социальными сетями преподавателей.</td>
                            <td class="p-4 text-slate-600">Раздел "Результаты" содержит верифицированные отзывы, ссылки на соцсети выпускников и сканы их работ. Полная прозрачность и защита от фейков.</td>
                        </tr>
                        <tr class="hover:bg-slate-50/50 transition-colors">
                            <td class="p-4 font-semibold text-slate-900">Бесплатный еженедельный контент-маркетинг амбассадоров</td>
                            <td class="p-4 text-slate-600">Редкие промо-вебинары, весь полезный контент скрыт за пейволлом или находится на общем YouTube-канале без жесткой привязки к конкретным амбассадорам.</td>
                            <td class="p-4 text-slate-600">Регулярные бесплатные вебинары от каждого преподавателя на их персональных YouTube-каналах. TG-боты амбассадоров делятся бесплатными конспектами, квизами и шпаргалками.</td>
                            <td class="p-4 text-slate-600">Еженедельные бесплатные марафоны в Telegram, закрытые интерактивные игры-боты от амбассадоров, вовлекающие в покупку платного продукта через личную пользу.</td>
                            <td class="p-4 text-slate-600">Огромная сетка бесплатных стримов (2–3 раза в неделю) от каждого преподавателя на YouTube (разборы СтатГрад, вариантов ФИПИ в реальном времени) и бесплатные TG-курсы.</td>
                        </tr>
                        <tr class="hover:bg-slate-50/50 transition-colors">
                            <td class="p-4 font-semibold text-slate-900">Интерактивный тест-драйв курса (демо-уроки без регистрации)</td>
                            <td class="p-4 text-slate-600">Для получения пробного урока необходимо оставить контактные данные и пройти вводный созвон с менеджером по продажам.</td>
                            <td class="p-4 text-slate-600">На лендинге можно посмотреть записи лучших открытых занятий амбассадоров и скачать к ним конспекты без обязательной отправки телефона.</td>
                            <td class="p-4 text-slate-600">Быстрый интерактивный демо-доступ через Telegram-бота в один клик для прохождения первого урока-игры от амбассадора.</td>
                            <td class="p-4 text-slate-600">Открытый доступ к первым 3–5 урокам годового курса на YouTube-каналах амбассадоров и встроенные плееры на посадочных страницах с полной базой материалов.</td>
                        </tr>
                        <tr class="hover:bg-slate-50/50 transition-colors">
                            <td class="p-4 font-semibold text-slate-900">Кросс-продажи и партнерские бандлы амбассадоров</td>
                            <td class="p-4 text-slate-600">Стандартные пакетные предложения (скидки при покупке нескольких предметов), не привязанные к коллаборациям преподавателей.</td>
                            <td class="p-4 text-slate-600">Программа лояльности с накоплением внутренней валюты Um-Coins, которую можно тратить на лимитированный мерч, разработанный совместно с амбассадорами.</td>
                            <td class="p-4 text-slate-600">Масштабные розыгрыши ценных призов (техника, мерч) в прямом эфире амбассадоров среди тех, кто пригласил друзей или сделал репост.</td>
                            <td class="p-4 text-slate-600">Скидки на смежные предметы при покупке бандла (например, Математика от Эрика + Физика от Сани). Амбассадоры активно продвигают друг друга, организуя совместные стримы.</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
            
            <section class="bg-white rounded-2xl p-6 shadow-sm border border-slate-200 flex flex-col h-full">
                <div class="mb-6">
                    <h2 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                        <span>🛡️</span> Адаптация E-E-A-T под лендинги амбассадоров
                    </h2>
                    <p class="text-sm text-slate-500 mt-2">
                        Перевод руководства для асессоров на язык метрик страниц курсов Exams. Кликните на вкладки для детализации.
                    </p>
                </div>

                <div class="flex border-b border-slate-200 mb-4 overflow-x-auto custom-scroll pb-2">
                    <button class="eeat-tab-btn active px-4 py-2 font-semibold text-brand-600 border-b-2 border-brand-600 whitespace-nowrap" data-target="tab-experience">Experience (Опыт)</button>
                    <button class="eeat-tab-btn px-4 py-2 font-medium text-slate-500 hover:text-slate-700 whitespace-nowrap" data-target="tab-expertise">Expertise (Экспертиза)</button>
                    <button class="eeat-tab-btn px-4 py-2 font-medium text-slate-500 hover:text-slate-700 whitespace-nowrap" data-target="tab-authority">Authority (Авторитет)</button>
                    <button class="eeat-tab-btn px-4 py-2 font-medium text-slate-500 hover:text-slate-700 whitespace-nowrap" data-target="tab-trust">Trust (Доверие)</button>
                </div>

                <div id="tab-experience" class="eeat-tab-content flex-grow">
                    <h3 class="font-bold text-slate-800 mb-2">Демонстрация реального опыта преподавания</h3>
                    <ul class="space-y-3 text-slate-600 text-sm">
                        <li class="flex gap-2"><span>✅</span> <strong>Личный опыт сдачи:</strong> Блоки с результатами сдачи ЕГЭ самим амбассадором (сканы сертификатов, видео "Как я сдал на 100").</li>
                        <li class="flex gap-2"><span>✅</span> <strong>UGC & Истории:</strong> Интеграция реальных отзывов учеников амбассадора с прошлых потоков (до прихода в Skysmart) с указанием баллов (До/После).</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Микро-форматы:</strong> Видео-сниппеты, где амбассадор решает реальную задачу с ЕГЭ прошлых лет у доски.</li>
                    </ul>
                </div>
                
                <div id="tab-expertise" class="eeat-tab-content hidden flex-grow">
                    <h3 class="font-bold text-slate-800 mb-2">Глубина знаний и структура курса</h3>
                    <ul class="space-y-3 text-slate-600 text-sm">
                        <li class="flex gap-2"><span>✅</span> <strong>Именованные фреймворки:</strong> Создание уникальных названий для методик. Например: "Система подготовки по Математике Х-3 от [Имя Блогера]".</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Детализация программы:</strong> Не просто "Урок 1: Кинематика", а детальный разбор подтем, которые проверяются на реальном экзамене.</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Связка с ФИПИ:</strong> Прямые ссылки и упоминания стандартов ФИПИ и кодификаторов текущего года.</li>
                    </ul>
                </div>

                <div id="tab-authority" class="eeat-tab-content hidden flex-grow">
                    <h3 class="font-bold text-slate-800 mb-2">Внешние сигналы и Knowledge Graph</h3>
                    <ul class="space-y-3 text-slate-600 text-sm">
                        <li class="flex gap-2"><span>✅</span> <strong>Социальный капитал:</strong> Вывод счетчиков подписчиков YouTube/Telegram амбассадора прямо на первый экран лендинга.</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Внешние подтверждения:</strong> Публикация оригинальных исследований амбассадора (например, "Анализ типичных ошибок ЕГЭ 2025") на внешних ресурсах с упоминанием Skysmart, но без обязательной ссылки (усиливает Entity).</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Микроразметка:</strong> Внедрение Schema.org <code>Course</code> и <code>Person</code>, связывая страницу курса со страницей блогера в Википедии или соцсетях.</li>
                    </ul>
                </div>

                <div id="tab-trust" class="eeat-tab-content hidden flex-grow">
                    <h3 class="font-bold text-slate-800 mb-2">Снижение Risk-паттернов алгоритмов</h3>
                    <ul class="space-y-3 text-slate-600 text-sm">
                        <li class="flex gap-2"><span>✅</span> <strong>Прозрачность цены:</strong> Четкие тарифы без скрытых платежей. Информация о возврате средств.</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Ответственность:</strong> Блок "Кто проверяет домашки" (кураторы Skysmart vs сам амбассадор) — честность формирует доверие.</li>
                        <li class="flex gap-2"><span>✅</span> <strong>Юридическая чистота:</strong> Ссылки на образовательную лицензию Skysmart в подвале каждой страницы амбассадора.</li>
                    </ul>
                </div>
            </section>

            <section class="bg-white rounded-2xl p-6 shadow-sm border border-slate-200 flex flex-col h-full">
                <div class="mb-6">
                    <h2 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                        <span>🎯</span> NavBoost: Оправдание клика
                    </h2>
                    <p class="text-sm text-slate-500 mt-2">
                        Алгоритмы фиксируют удовлетворенность через отсутствие возврата в выдачу (снижение BadClicks). Схема построения контента на странице курса для удержания внимания.
                    </p>
                </div>

                <div class="flex-grow flex flex-col justify-center space-y-4">
                    <div class="funnel-step bg-brand-50 border-l-4 border-brand-500 p-4 rounded-r-lg relative">
                        <div class="absolute -left-[24px] top-1/2 -translate-y-1/2 bg-white border-2 border-brand-500 text-brand-600 font-bold rounded-full w-8 h-8 flex items-center justify-center text-sm">1</div>
                        <h4 class="font-bold text-brand-900 ml-4">Сильный Интро-абзац</h4>
                        <p class="text-sm text-slate-600 ml-4 mt-1">Сразу даем обещание результата. <em>"Годовая подготовка к ЕГЭ по информатике с [Имя]. Выведем на 85+ баллов по авторской методике даже с нуля."</em></p>
                    </div>
                    <div class="funnel-step bg-slate-50 border-l-4 border-slate-400 p-4 rounded-r-lg relative ml-4">
                        <div class="absolute -left-[24px] top-1/2 -translate-y-1/2 bg-white border-2 border-slate-400 text-slate-600 font-bold rounded-full w-8 h-8 flex items-center justify-center text-sm">2</div>
                        <h4 class="font-bold text-slate-800 ml-4">Якорный список выгод</h4>
                        <p class="text-sm text-slate-600 ml-4 mt-1">Четкое "что вы получите": 80 видеоуроков, 12 пробников, личный куратор. Снижает показатель отказов в первые 5 секунд.</p>
                    </div>
                    <div class="funnel-step bg-slate-50 border-l-4 border-slate-400 p-4 rounded-r-lg relative ml-8">
                        <div class="absolute -left-[24px] top-1/2 -translate-y-1/2 bg-white border-2 border-slate-400 text-slate-600 font-bold rounded-full w-8 h-8 flex items-center justify-center text-sm">3</div>
                        <h4 class="font-bold text-slate-800 ml-4">Глубокое взаимодействие</h4>
                        <p class="text-sm text-slate-600 ml-4 mt-1">Интерактивный блок с примером урока амбассадора или тестом на текущий уровень знаний. Увеличивает глубину сессии (GoodClick).</p>
                    </div>
                    <div class="funnel-step bg-accent-50 border-l-4 border-accent-500 p-4 rounded-r-lg relative ml-12">
                        <div class="absolute -left-[24px] top-1/2 -translate-y-1/2 bg-white border-2 border-accent-500 text-accent-600 font-bold rounded-full w-8 h-8 flex items-center justify-center text-sm">4</div>
                        <h4 class="font-bold text-accent-900 ml-4">Мини-резюме и CTA</h4>
                        <p class="text-sm text-slate-600 ml-4 mt-1">В конце лендинга краткая выжимка. Пользователь дочитавший до конца = подтвержденный качественный интент для поиска.</p>
                    </div>
                </div>
            </section>

            <section class="bg-white rounded-2xl p-6 shadow-sm border border-slate-200">
                <div class="mb-4">
                    <h2 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                        <span>📊</span> Сравнение E-E-A-T Профилей
                    </h2>
                    <p class="text-sm text-slate-500 mt-2">
                        Оценка текущего состояния посадочных страниц Skysmart в сравнении с главным конкурентом и целевой моделью на 2026 год.
                    </p>
                </div>
                <div class="chart-container">
                    <canvas id="eeatRadarChart"></canvas>
                </div>
            </section>

            <section class="bg-white rounded-2xl p-6 shadow-sm border border-slate-200">
                <div class="mb-4 flex flex-col sm:flex-row sm:items-center sm:justify-between gap-2">
                    <div>
                        <h2 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                            <span>🚀</span> Динамика оплат и Выход в ТОП
                        </h2>
                        <p class="text-sm text-slate-500 mt-1">
                            Корреляция роста процента видимости в ТОПе и количества оплат (всего 103 за цикл) на основе предоставленных расчетов.
                        </p>
                    </div>
                    <div class="inline-flex rounded-lg border border-slate-200 p-1 bg-slate-50 self-start">
                        <button id="btn-monthly" class="px-3 py-1 text-xs font-semibold rounded-md bg-white text-slate-800 shadow-sm transition-all">Помесячно</button>
                        <button id="btn-cumulative" class="px-3 py-1 text-xs font-medium rounded-md text-slate-600 hover:text-slate-800 transition-all">Нарастающий</button>
                    </div>
                </div>
                <div class="chart-container">
                    <canvas id="impactBarChart"></canvas>
                </div>
            </section>
        </div>

        <section class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200">
            <div class="flex justify-between items-end mb-6 border-b border-slate-200 pb-4">
                <div>
                    <h2 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                        <span>📋</span> Roadmap внедрения для Exams
                    </h2>
                </div>
                <div class="text-right">
                    <span class="text-3xl font-bold text-brand-600" id="progress-text">0%</span>
                    <p class="text-xs text-slate-400 font-medium uppercase tracking-wider">Готовность</p>
                </div>
            </div>

            <div class="w-full bg-slate-100 rounded-full h-2.5 mb-8">
                <div id="progress-bar" class="bg-brand-500 h-2.5 rounded-full transition-all duration-500 ease-out" style="width: 0%"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="space-y-3">
                    <h3 class="font-bold text-slate-700 uppercase text-xs tracking-wider mb-4">Этап 1: Структура и Контент (On-page)</h3>
                    
                    <label class="flex items-start gap-3 p-3 hover:bg-slate-50 rounded-lg cursor-pointer transition-colors border border-transparent hover:border-slate-200">
                        <input type="checkbox" class="task-checkbox mt-1 w-5 h-5 text-brand-600 rounded focus:ring-brand-500 border-slate-300">
                        <div>
                            <p class="font-medium text-slate-800 text-sm">Переписать интро-блоки (NavBoost)</p>
                            <p class="text-xs text-slate-500 mt-1">Добавить жесткие обещания результатов и якорные списки на первые экраны лендингов амбассадоров.</p>
                        </div>
                    </label>

                    <label class="flex items-start gap-3 p-3 hover:bg-slate-50 rounded-lg cursor-pointer transition-colors border border-transparent hover:border-slate-200">
                        <input type="checkbox" class="task-checkbox mt-1 w-5 h-5 text-brand-600 rounded focus:ring-brand-500 border-slate-300">
                        <div>
                            <p class="font-medium text-slate-800 text-sm">Внедрить блоки "Личный опыт" (Experience)</p>
                            <p class="text-xs text-slate-500 mt-1">Добавить сертификаты ЕГЭ преподавателей и видео-разборы сложных задач прямо на посадочные.</p>
                        </div>
                    </label>

                    <label class="flex items-start gap-3 p-3 hover:bg-slate-50 rounded-lg cursor-pointer transition-colors border border-transparent hover:border-slate-200">
                        <input type="checkbox" class="task-checkbox mt-1 w-5 h-5 text-brand-600 rounded focus:ring-brand-500 border-slate-300">
                        <div>
                            <p class="font-medium text-slate-800 text-sm">Упаковка "Именованных фреймворков"</p>
                            <p class="text-xs text-slate-500 mt-1">Выделить методики преподавателей в авторские названия для генерации уникальных брендовых запросов.</p>
                        </div>
                    </label>
                </div>

                <div class="space-y-3">
                    <h3 class="font-bold text-slate-700 uppercase text-xs tracking-wider mb-4">Этап 2: Внешние сигналы и Техническая часть</h3>
                    
                    <label class="flex items-start gap-3 p-3 hover:bg-slate-50 rounded-lg cursor-pointer transition-colors border border-transparent hover:border-slate-200">
                        <input type="checkbox" class="task-checkbox mt-1 w-5 h-5 text-brand-600 rounded focus:ring-brand-500 border-slate-300">
                        <div>
                            <p class="font-medium text-slate-800 text-sm">Внедрить Schema.org (Course & Person)</p>
                            <p class="text-xs text-slate-500 mt-1">Связать профили амбассадоров с их соцсетями в разметке для усиления Entity в Knowledge Graph.</p>
                        </div>
                    </label>

                    <label class="flex items-start gap-3 p-3 hover:bg-slate-50 rounded-lg cursor-pointer transition-colors border border-transparent hover:border-slate-200">
                        <input type="checkbox" class="task-checkbox mt-1 w-5 h-5 text-brand-600 rounded focus:ring-brand-500 border-slate-300">
                        <div>
                            <p class="font-medium text-slate-800 text-sm">PR: Упоминания без ссылок (Authority)</p>
                            <p class="text-xs text-slate-500 mt-1">Запустить посевы исследований от лица амбассадоров (статистика сдачи) на внешних площадках с упоминанием Skysmart.</p>
                        </div>
                    </label>

                    <label class="flex items-start gap-3 p-3 hover:bg-slate-50 rounded-lg cursor-pointer transition-colors border border-transparent hover:border-slate-200">
                        <input type="checkbox" class="task-checkbox mt-1 w-5 h-5 text-brand-600 rounded focus:ring-brand-500 border-slate-300">
                        <div>
                            <p class="font-medium text-slate-800 text-sm">Оптимизация Trust-сигналов</p>
                            <p class="text-xs text-slate-500 mt-1">Вывести блоки гарантий, юр. информацию о лицензии и чёткие правила возврата в видимую зону лендинга.</p>
                        </div>
                    </label>
                </div>
            </div>
        </section>

    </main>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            
            const tabBtns = document.querySelectorAll('.eeat-tab-btn');
            const tabContents = document.querySelectorAll('.eeat-tab-content');

            tabBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    tabBtns.forEach(b => {
                        b.classList.remove('text-brand-600', 'border-b-2', 'border-brand-600', 'active');
                        b.classList.add('text-slate-500');
                    });
                    
                    btn.classList.add('text-brand-600', 'border-b-2', 'border-brand-600', 'active');
                    btn.classList.remove('text-slate-500');

                    tabContents.forEach(content => content.classList.add('hidden'));

                    const targetId = btn.getAttribute('data-target');
                    document.getElementById(targetId).classList.remove('hidden');
                });
            });

            const checkboxes = document.querySelectorAll('.task-checkbox');
            const progressBar = document.getElementById('progress-bar');
            const progressText = document.getElementById('progress-text');

            function updateProgress() {
                const total = checkboxes.length;
                const checked = document.querySelectorAll('.task-checkbox:checked').length;
                const percentage = Math.round((checked / total) * 100);
                
                progressBar.style.width = `${percentage}%`;
                progressText.innerText = `${percentage}%`;

                if(percentage === 100) {
                    progressText.classList.add('text-green-500');
                    progressText.classList.remove('text-brand-600');
                    progressBar.classList.add('bg-green-500');
                    progressBar.classList.remove('bg-brand-500');
                } else {
                    progressText.classList.remove('text-green-500');
                    progressText.classList.add('text-brand-600');
                    progressBar.classList.remove('bg-green-500');
                    progressBar.classList.add('bg-brand-500');
                }
            }

            checkboxes.forEach(box => {
                box.addEventListener('change', updateProgress);
            });

            Chart.defaults.font.family = "'Inter', sans-serif";
            Chart.defaults.color = '#64748b';

            const ctxRadar = document.getElementById('eeatRadarChart').getContext('2d');
            const eeatRadarChart = new Chart(ctxRadar, {
                type: 'radar',
                data: {
                    labels: ['Experience (Опыт)', 'Expertise (Экспертиза)', 'Authority (Авторитет)', 'Trust (Доверие)'],
                    datasets: [
                        {
                            label: 'Skysmart (Текущий)',
                            data: [60, 85, 65, 80],
                            backgroundColor: 'rgba(148, 163, 184, 0.2)',
                            borderColor: '#94a3b8',
                            pointBackgroundColor: '#94a3b8',
                            borderWidth: 2
                        },
                        {
                            label: 'Конкурент (el-ed.ru)',
                            data: [80, 70, 85, 70],
                            backgroundColor: 'rgba(245, 158, 11, 0.2)',
                            borderColor: '#f59e0b',
                            pointBackgroundColor: '#f59e0b',
                            borderWidth: 2
                        },
                        {
                            label: 'Skysmart (Цель 2026)',
                            data: [95, 95, 90, 95],
                            backgroundColor: 'rgba(59, 130, 246, 0.2)',
                            borderColor: '#3b82f6',
                            pointBackgroundColor: '#3b82f6',
                            borderWidth: 2
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        r: {
                            angleLines: { color: 'rgba(0,0,0,0.05)' },
                            grid: { color: 'rgba(0,0,0,0.05)' },
                            pointLabels: {
                                font: { size: 12, weight: '600' },
                                color: '#334155'
                            },
                            ticks: { display: false, min: 0, max: 100 }
                        }
                    },
                    plugins: {
                        legend: { position: 'bottom', labels: { usePointStyle: true, boxWidth: 8 } },
                        tooltip: {
                            backgroundColor: 'rgba(15, 23, 42, 0.9)',
                            padding: 12,
                            cornerRadius: 8
                        }
                    }
                }
            });

            const months = ['Июль', 'Август', 'Сентябрь', 'Октябрь', 'Ноябрь', 'Декабрь', 'Январь', 'Февраль', 'Март', 'Апрель', 'Май', 'Июнь'];
            
            // Базовые помесячные значения из Excel-файла (точно по столбцу "Оплат" из прикрепленного файла)
            const monthlySales = [0, 1, 2, 5, 5, 8, 11, 13, 14, 14, 15, 15];
            
            // Рассчитываем точный нарастающий итог:
            const cumulativeSales = [];
            monthlySales.reduce((acc, val, i) => {
                cumulativeSales[i] = acc + val;
                return acc + val;
            }, 0);
            
            // Процент выхода в ТОП (из файла): 1%, 5%, 10%, 30%, 30%, 50%, 70%, 85%, 90%, 95%, 100%, 100%
            const topVisibility = [1, 5, 10, 30, 30, 50, 70, 85, 90, 95, 100, 100];

            const ctxBar = document.getElementById('impactBarChart').getContext('2d');
            const impactBarChart = new Chart(ctxBar, {
                type: 'bar',
                data: {
                    labels: months,
                    datasets: [
                        {
                            label: 'Оплат (помесячно)',
                            data: monthlySales,
                            backgroundColor: '#3b82f6',
                            borderRadius: 4,
                            yAxisID: 'yPayments',
                            order: 2
                        },
                        {
                            label: 'Выход в ТОП (%)',
                            data: topVisibility,
                            borderColor: '#f59e0b',
                            backgroundColor: 'transparent',
                            borderWidth: 3,
                            pointBackgroundColor: '#f59e0b',
                            pointRadius: 4,
                            type: 'line',
                            yAxisID: 'yTop',
                            order: 1
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        yPayments: {
                            type: 'linear',
                            position: 'left',
                            beginAtZero: true,
                            max: 18, // начальный максимум для помесячного отображения
                            title: { display: true, text: 'Количество оплат', font: { size: 11, weight: 'bold' } },
                            grid: { color: 'rgba(0,0,0,0.05)' },
                            border: { display: false }
                        },
                        yTop: {
                            type: 'linear',
                            position: 'right',
                            beginAtZero: true,
                            max: 100,
                            title: { display: true, text: 'Выход в ТОП (%)', font: { size: 11, weight: 'bold' } },
                            grid: { drawOnChartArea: false },
                            border: { display: false },
                            ticks: {
                                callback: function(value) { return value + '%'; }
                            }
                        },
                        x: {
                            grid: { display: false },
                            border: { display: false }
                        }
                    },
                    plugins: {
                        legend: { position: 'bottom', labels: { usePointStyle: true, boxWidth: 8 } },
                        tooltip: {
                            backgroundColor: 'rgba(15, 23, 42, 0.9)',
                            padding: 12,
                            cornerRadius: 8,
                            callbacks: {
                                label: function(context) {
                                    let label = context.dataset.label || '';
                                    if (label) {
                                        label += ': ';
                                    }
                                    if (context.datasetIndex === 1) {
                                        label += context.parsed.y + '%';
                                    } else {
                                        label += context.parsed.y;
                                    }
                                    return label;
                                }
                            }
                        }
                    }
                }
            });

            const btnMonthly = document.getElementById('btn-monthly');
            const btnCumulative = document.getElementById('btn-cumulative');

            btnMonthly.addEventListener('click', () => {
                btnMonthly.className = 'px-3 py-1 text-xs font-semibold rounded-md bg-white text-slate-800 shadow-sm transition-all';
                btnCumulative.className = 'px-3 py-1 text-xs font-medium rounded-md text-slate-600 hover:text-slate-800 transition-all';
                
                impactBarChart.data.datasets[0].data = monthlySales;
                impactBarChart.data.datasets[0].label = 'Оплат (помесячно)';
                
                // Сбрасываем шкалу под помесячные значения для лучшего масштабирования
                impactBarChart.options.scales.yPayments.max = 18;
                impactBarChart.update();
            });

            btnCumulative.addEventListener('click', () => {
                btnCumulative.className = 'px-3 py-1 text-xs font-semibold rounded-md bg-white text-slate-800 shadow-sm transition-all';
                btnMonthly.className = 'px-3 py-1 text-xs font-medium rounded-md text-slate-600 hover:text-slate-800 transition-all';
                
                impactBarChart.data.datasets[0].data = cumulativeSales;
                impactBarChart.data.datasets[0].label = 'Оплат (нарастающий итог)';
                
                // Корректируем шкалу под кумулятивные значения, чтобы ничего не обрезалось (макс 103)
                impactBarChart.options.scales.yPayments.max = 110;
                impactBarChart.update();
            });

        });
    </script>
</body>
</html>
