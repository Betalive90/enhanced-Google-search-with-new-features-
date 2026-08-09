# enhanced-Google-search-with-new-features-
enhanced google search with new features with out replacement google engine search standards i have added overly 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><search>google</search></title>
    <meta name="description" content="صفحة بحث جوجل">
    <meta name="keywords" content="بحث, جوجل, بحث Google">
   <script src="https://cdn.tailwindcss.com"></script>
   <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        'dark-bg': '#181818',
                        'dark-card': '#2a2a2a',
                        'dark-border': '#404040'
                    }
                }
            }
        }
    </script>
    <style>
        /* ==========================================
           CUSTOMIZATION SECTION - Edit colors here
           ========================================== */
        :root {
            /* Primary Colors */
            --color-primary: #5D5CDE;
            --color-primary-hover: #4a4ab8;
            --color-secondary: #764ba2;

            /* Background Colors */
            --color-bg-light: #1981e9;
            --color-bg-dark: #181818;
            --color-card-light: #ffffff;
            --color-card-dark: #2a2a2a;

            /* Accent Colors */
            --color-success: #10b981;
            --color-warning: #f59e0b;
            --color-danger: #ef4444;
            --color-info: #3b82f6;

            /* Social Media Colors */
            --color-facebook: #1877f2;
            --color-twitter: #1da1f2;
            --color-instagram: #e4405f;
            --color-linkedin: #0077b5;
            --color-youtube: #ff0000;
            --color-github: #333333;

            /* Text Colors */
            --color-text-primary: #1f2937;
            --color-text-secondary: #6b7280;
            --color-text-light: #ffffff;
        }

        .gradient-bg {
            background: linear-gradient(135deg, var(--color-primary) 0%, var(--color-secondary) 100%);
        }

        .animate-pulse-slow {
            animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }

        .toggle-switch {
            appearance: none;
            width: 48px;
            height: 24px;
            border-radius: 12px;
            background: #e5e7eb;
            position: relative;
            cursor: pointer;
            transition: all 0.3s;
        }

        .toggle-switch:checked {
            background: var(--color-primary);
        }

        .toggle-switch::before {
            content: '';
            position: absolute;
            top: 2px;
            left: 2px;
            width: 20px;
            height: 20px;
            background: white;
            border-radius: 50%;
            transition: all 0.3s;
        }

        .toggle-switch:checked::before {
            transform: translateX(24px);
        }

        .side-menu {
            position: fixed;
            top: 0;
            right: -450px;
            width: 450px;
            height: 100vh;
            background: white;
            box-shadow: -5px 0 20px rgba(0,0,0,0.1);
            transition: right 0.3s ease;
            z-index: 100;
            overflow-y: auto;
        }

        .dark .side-menu {
            background: var(--color-card-dark);
        }

        .side-menu.open {
            right: 0;
        }

        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s;
            z-index: 99;
        }

        .overlay.active {
            opacity: 1;
            visibility: visible;
        }

        .badge {
            display: inline-block;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 11px;
            font-weight: 600;
            text-transform: uppercase;
        }

        .badge-new {
            background: var(--color-success);
            color: white;
        }

        .badge-beta {
            background: #f59e0b;
            color: white;
            animation: pulse 2s infinite;
        }

        .badge-security {
            background: var(--color-danger);
            color: white;
        }

        .badge-feature {
            background: var(--color-info);
            color: white;
        }

        @keyframes slideIn {
            from {
                transform: translateY(20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .animate-slide-in {
            animation: slideIn 0.3s ease-out;
        }

        .history-item {
            transition: all 0.2s;
            cursor: pointer;
        }

        .history-item:hover {
            transform: translateX(-5px);
            background: rgba(93, 92, 222, 0.1);
        }

        .social-link {
            transition: all 0.3s;
        }

        .social-link:hover {
            transform: translateY(-3px);
        }

        @media (max-width: 640px) {
            .side-menu {
                width: 100%;
                right: -100%;
            }
        }
    </style>
</head>
<body>
    
</body>
</html>
