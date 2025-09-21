<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darshak Bisane</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            /* A subtle, light gradient for the background */
            background: linear-gradient(135deg, #e0f6ff 0%, #e8f0ff 100%);
            font-family: 'Inter', sans-serif;
        }

        /* Custom scrollbar for a polished look */
        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }

        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }

        .dev-icon-wrapper {
            transition: transform 0.2s ease-in-out, filter 0.2s ease-in-out;
            filter: grayscale(100%);
        }

        .dev-icon-wrapper:hover {
            transform: scale(1.1);
            filter: grayscale(0%);
        }

        /* Keyframes for a smooth slide-in from the bottom */
        @keyframes slideInUp {
            from {
                transform: translateY(20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Keyframes for a simple fade-in effect */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body class="min-h-screen p-4 sm:p-8 flex items-center justify-center">

    <!-- Main Content Container with animations -->
    <div class="container max-w-5xl w-full mx-auto bg-gray-50 p-6 sm:p-12 rounded-3xl shadow-2xl border border-gray-100 transform transition-all duration-300 hover:scale-[1.01] animate-[slideInUp_0.8s_ease-out_forwards]">
        
        <!-- Header Section -->
        <header class="text-center mb-8 animate-[fadeIn_0.5s_ease-in_0.5s_forwards] opacity-0">
            <h1 class="text-3xl sm:text-4xl font-bold text-gray-800">Hi 👋, I'm Darshak Bisane</h1>
            <h3 class="text-xl sm:text-2xl font-medium text-gray-600 mt-2">A passionate Mern Stack & ML developer from India</h3>
        </header>

        <!-- Trophy Section -->
        <div class="flex justify-center mb-8 animate-[fadeIn_0.5s_ease-in_0.7s_forwards] opacity-0">
            <a href="https://github.com/ryo-ma/github-profile-trophy" target="_blank" rel="noopener noreferrer">
                <img src="https://github-profile-trophy.vercel.app/?username=darshakbisane" alt="darshakbisane" class="rounded-xl shadow-md transition-transform duration-300 hover:scale-105" />
            </a>
        </div>

        <!-- Bio & Contact Info Section -->
        <section class="bg-gray-50 p-6 rounded-2xl shadow-inner mb-8 space-y-4 animate-[fadeIn_0.5s_ease-in_0.9s_forwards] opacity-0">
            <p class="text-gray-700 leading-relaxed">
                <strong class="text-gray-900">🌱 I’m currently learning:</strong> ARTIFICIAL INTELLIGENCE & MACHINE LEARNING
            </p>
            <p class="text-gray-700 leading-relaxed">
                <strong class="text-gray-900">💬 Ask me about:</strong> REACT❤️, PYTHON🩷, NODEJS🧡, MONGODB💛, CSS💚
            </p>
            <p class="text-gray-700 leading-relaxed">
                <strong class="text-gray-900">📫 How to reach me:</strong> <a href="mailto:darshak123321@gmail.com" class="text-blue-600 hover:text-blue-800 transition-colors duration-200">darshak123321@gmail.com</a>
            </p>
        </section>

        <!-- Connect with me Section -->
        <section class="mb-8 animate-[fadeIn_0.5s_ease-in_1.1s_forwards] opacity-0">
            <h3 class="text-2xl font-semibold text-gray-800 mb-4 text-center">Connect with me:</h3>
            <div class="flex justify-center items-center space-x-6">
                <a href="https://linkedin.com/in/darshakbisane" target="blank" class="transition-transform duration-300 transform hover:scale-125">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="darshakbisane" class="h-8 w-10"/>
                </a>
                <a href="https://instagram.com/bisane_darshak" target="blank" class="transition-transform duration-300 transform hover:scale-125">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="bisane_darshak" class="h-8 w-10"/>
                </a>
            </div>
        </section>

        <!-- Languages and Tools Section -->
        <section class="mb-8 animate-[fadeIn_0.5s_ease-in_1.3s_forwards] opacity-0">
            <h3 class="text-2xl font-semibold text-gray-800 mb-6 text-center">Languages and Tools:</h3>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="https://developer.android.com" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a>
                <a href="https://getbootstrap.com" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a>
                <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a>
                <a href="https://www.chartjs.org" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40"/> </a>
                <a href="https://codeigniter.com" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://cdn.worldvectorlogo.com/logos/codeigniter.svg" alt="codeigniter" width="40" height="40"/> </a>
                <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a>
                <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>
                <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a>
                <a href="https://expressjs.com" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a>
                <a href="https://www.figma.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a>
                <a href="https://firebase.google.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a>
                <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a>
                <a href="https://flutter.dev" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a>
                <a href="https://git-scm.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
                <a href="https://gridsome.org/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/gridsome/gridsome-icon.svg" alt="gridsome" width="40" height="40"/> </a>
                <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>
                <a href="https://www.java.com" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a>
                <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
                <a href="https://kotlinlang.org" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a>
                <a href="https://laravel.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="laravel" width="40" height="40"/> </a>
                <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a>
                <a href="https://www.mysql.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>
                <a href="https://nextjs.org/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a>
                <a href="https://nodejs.org" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a>
                <a href="https://www.oracle.com/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a>
                <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
                <a href="https://www.php.net" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a>
                <a href="https://postman.com" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a>
                <a href="https://www.python.org" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
                <a href="https://pytorch.org/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a>
                <a href="https://reactjs.org/" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a>
                <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer" class="dev-icon-wrapper"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a>
            </div>
        </section>

        <!-- GitHub Stats Section -->
        <section class="flex flex-col md:flex-row justify-between items-center gap-6 animate-[fadeIn_0.5s_ease-in_1.5s_forwards] opacity-0">
            <div class="w-full md:w-1/2">
                <img src="https://github-readme-stats.vercel.app/api/top-langs?username=darshakbisane&show_icons=true&locale=en&layout=compact" alt="darshakbisane" class="w-full h-auto rounded-xl shadow-md transition-transform duration-300 hover:scale-105" />
            </div>
            <div class="w-full md:w-1/2">
                <img src="https://github-readme-stats.vercel.app/api?username=darshakbisane&show_icons=true&locale=en" alt="darshakbisane" class="w-full h-auto rounded-xl shadow-md transition-transform duration-300 hover:scale-105" />
            </div>
            <div class="w-full md:w-1/2">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=darshakbisane&" alt="darshakbisane" class="w-full h-auto rounded-xl shadow-md transition-transform duration-300 hover:scale-105" />
            </div>
        </section>

    </div>
</body>
</html>

