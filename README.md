<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title> ICON BIOTRONICS | Biomedical Engineering Solutions</title>

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>

    <!-- Tailwind Config -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        "icon-blue": "#004AAD",
                        "icon-teal": "#00A896",
                        "icon-bg": "#F3F4F6",
                        "whatsapp-green": "#25D366",
                    },
                },
            },
        };
    </script>

    <style>
        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', sans-serif;
            color: #1f2937;
        }

        .hero-gradient {
            background: linear-gradient(180deg, #f3f4f6 0%, #e7f7f5 100%);
        }
    </style>
</head>



<body class="bg-icon-bg">

    <!-- ========================================================= -->
    <!-- HEADER -->
    <!-- ========================================================= -->
    <header class="sticky top-0 z-50 bg-white shadow-xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4 md:justify-start md:space-x-10">

                <!-- Logo -->
                <div class="flex justify-start lg:w-0 lg:flex-1">
                    <a href="#hero" class="flex items-center space-x-2 text-3xl font-extrabold text-icon-blue">
                        <i data-lucide="zap" class="h-6 w-6 text-icon-teal"></i>
                        <span>ICON BIOTRONICS</span>
                    </a>
                </div>

                <!-- Desktop Menu -->
                <nav class="hidden md:flex space-x-8 font-semibold text-gray-700">
                    <a href="#services" class="hover:text-icon-blue">Core Services</a>
                    <a href="#catalog" class="hover:text-icon-blue">Product Catalog</a>
                    <a href="#dental" class="hover:text-icon-blue">Dental Solutions</a>
                    <a href="#compliance" class="hover:text-icon-blue">Quality Assurance</a>
                    <a href="#support" class="hover:text-icon-blue">Support</a>
                    <a href="#contact" class="hover:text-icon-blue">Contact</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-button" class="md:hidden p-2 rounded-md bg-white">
                    <i data-lucide="menu" class="h-6 w-6"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t shadow-lg">
            <nav class="flex flex-col space-y-4 p-6 text-lg font-semibold">
                <a href="#services" class="hover:text-icon-blue">Core Services</a>
                <a href="#catalog" class="hover:text-icon-blue">Product Catalog</a>
                <a href="#dental" class="hover:text-icon-blue">Dental Solutions</a>
                <a href="#compliance" class="hover:text-icon-blue">Quality Assurance</a>
                <a href="#support" class="hover:text-icon-blue">Support</a>
                <a href="#contact" class="hover:text-icon-blue">Contact</a>
            </nav>
        </div>
    </header>



    <!-- ========================================================= -->
    <!-- HERO -->
    <!-- ========================================================= -->
    <section id="hero" class="hero-gradient min-h-screen flex items-center justify-center text-center px-6">
        <div>
            <h1 class="text-5xl md:text-6xl font-extrabold text-icon-blue mb-6">
                Biomedical Engineering Solutions
            </h1>

            <p class="text-xl md:text-2xl text-gray-600 max-w-3xl mx-auto mb-8">
                Reliable, compliant, and innovative medical equipment and dental systems engineered to perfection.
            </p>

            <a href="#contact"
                class="inline-block bg-icon-teal text-white font-semibold text-xl px-10 py-4 rounded-lg shadow-lg hover:bg-teal-600 transition">
                Get a Consultation
            </a>
        </div>
    </section>



    <!-- ========================================================= -->
    <!-- SERVICES -->
    <!-- ========================================================= -->
    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-4xl font-extrabold text-center text-icon-blue mb-16">
                Core Biomedical Services
            </h2>

            <div class="grid md:grid-cols-3 gap-12">

                <!-- Service -->
                <div class="bg-icon-bg p-10 rounded-xl shadow-md text-center">
                    <i data-lucide="activity" class="mx-auto h-12 w-12 text-icon-teal mb-4"></i>
                    <h3 class="text-2xl font-bold text-gray-800 mb-3">Medical Equipment Maintenance</h3>
                    <p class="text-gray-600">
                        Preventive and corrective maintenance for all medical devices with regulatory-grade reporting.
                    </p>
                </div>

                <div class="bg-icon-bg p-10 rounded-xl shadow-md text-center">
                    <i data-lucide="stethoscope" class="mx-auto h-12 w-12 text-icon-teal mb-4"></i>
                    <h3 class="text-2xl font-bold text-gray-800 mb-3">Diagnostics & Calibration</h3>
                    <p class="text-gray-600">
                        Precision calibration for critical biomedical systems following ISO 13485 and MOH UAE guidelines.
                    </p>
                </div>

                <div class="bg-icon-bg p-10 rounded-xl shadow-md text-center">
                    <i data-lucide="shield-check" class="mx-auto h-12 w-12 text-icon-teal mb-4"></i>
                    <h3 class="text-2xl font-bold text-gray-800 mb-3">Compliance Verification</h3>
                    <p class="text-gray-600">
                        Full compliance audits and quality assurance documentation delivered professionally.
                    </p>
                </div>

            </div>
        </div>
    </section>



    <!-- ========================================================= -->
    <!-- PRODUCT CATALOG -->
    <!-- ========================================================= -->
    <section id="catalog" class="py-20 bg-icon-bg">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-4xl font-extrabold text-center text-icon-blue mb-16">
                Medical Equipment Product Catalog
            </h2>

            <div class="grid md:grid-cols-3 gap-12">

                <div class="bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Patient Monitors</h3>
                    <p class="text-gray-600">High-accuracy monitors for clinical and surgical applications.</p>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Infusion Pumps</h3>
                    <p class="text-gray-600">Advanced volumetric and syringe infusion systems.</p>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Defibrillators</h3>
                    <p class="text-gray-600">Portable and AED defibrillators with high reliability.</p>
                </div>

            </div>
        </div>
    </section>



    <!-- ========================================================= -->
    <!-- DENTAL TECHNOLOGY -->
    <!-- ========================================================= -->
    <section id="dental" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-4xl font-extrabold text-center text-icon-blue mb-16">
                Advanced Dental Engineering Solutions
            </h2>

            <div class="grid md:grid-cols-2 gap-16">

                <div class="bg-icon-bg p-10 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold mb-4">Dental Chair Systems</h3>
                    <p class="text-gray-600">High-end chair units, suction motors, LED operations lights, and scalers.</p>
                </div>

                <div class="bg-icon-bg p-10 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold mb-4">Sterilization Equipment</h3>
                    <p class="text-gray-600">Class B autoclaves, ultrasonic cleaners, and instrument sterilization tools.</p>
                </div>

            </div>
        </div>
    </section>



    <!-- ========================================================= -->
    <!-- COMPLIANCE -->
    <!-- ========================================================= -->
    <section id="compliance" class="py-20 bg-icon-bg">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-4xl font-extrabold text-center text-icon-blue mb-16">
                Compliance & Safety Certifications
            </h2>

            <div class="grid md:grid-cols-3 gap-12">

                <div class="bg-white p-8 rounded-xl shadow-md text-center">
                    <i data-lucide="clipboard-check" class="h-12 w-12 mx-auto text-icon-teal mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">ISO 13485</h3>
                    <p class="text-gray-600">Certified biomedical documentation and traceability.</p>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-md text-center">
                    <i data-lucide="check-circle" class="h-12 w-12 mx-auto text-icon-teal mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">MOHAP Guidelines</h3>
                    <p class="text-gray-600">UAE Ministry of Health regulatory compliance.</p>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-md text-center">
                    <i data-lucide="file-check" class="h-12 w-12 mx-auto text-icon-teal mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Service Reporting</h3>
                    <p class="text-gray-600">Digitally signed compliance and calibration reports.</p>
                </div>

            </div>
        </div>
    </section>



    <!-- ========================================================= -->
    <!-- SUPPORT -->
    <!-- ========================================================= -->
    <section id="support" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-4xl font-extrabold text-center text-icon-blue mb-16">
                Customer Support & Service Plans
            </h2>

            <div class="grid md:grid-cols-2 gap-16">

                <div class="bg-icon-bg p-10 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold mb-4">Annual Maintenance Contracts</h3>
                    <p class="text-gray-600">Complete AMC packages for hospitals, clinics, and dental centers.</p>
                </div>

                <div class="bg-icon-bg p-10 rounded-xl shadow-md">
                    <h3 class="text-2xl font-bold mb-4">Emergency Repair</h3>
                    <p class="text-gray-600">24/7 on-call biomedical engineering response team.</p>
                </div>

            </div>
        </div>
    </section>



    <!-- ========================================================= -->
    <!-- CONTACT -->
    <!-- ========================================================= -->
    <section id="contact" class="py-20 bg-icon-bg">
        <div class="max-w-5xl mx-auto px-6 text-center">

            <h2 class="text-4xl font-extrabold text-icon-blue mb-8">
                Contact Us
            </h2>

            <p class="text-gray-700 text-lg mb-8">
                We are ready to support your medical engineering needs.
            </p>

            <a href="https://wa.me/971553252589"
                class="inline-flex items-center space-x-2 bg-whatsapp-green text-white px-8 py-4 rounded-lg shadow-lg text-xl font-semibold hover:bg-green-600 transition">
                <i data-lucide="message-circle" class="h-6 w-6"></i>
                <span>WhatsApp Us</span>
            </a>

        </div>
    </section>



    <!-- ========================================================= -->
    <!-- FOOTER -->
    <!-- ========================================================= -->
    <footer class="bg-gray-900 text-gray-300 py-12">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <p class="text-lg">© 2025 ICON BIOTRONICS. All Rights Reserved.</p>
        </div>
    </footer>



    <!-- ========================================================= -->
    <!-- SCRIPTS -->
    <!-- ========================================================= -->
    <script>
        // Initialize icons
        lucide.createIcons();

        // Mobile menu logic
        const btn = document.getElementById("mobile-menu-button");
        const menu = document.getElementById("mobile-menu");

        btn.addEventListener("click", () => {
            menu.classList.toggle("hidden");
        });
    </script>

</body>
</html>
