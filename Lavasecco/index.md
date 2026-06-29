<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lavasecco Niki | Cremona</title>
    <meta name="description" content="Lavanderia, lavasecco, sartoria e vendita detersivi a Cremona. Qualità e cura per i tuoi capi.">
    
    <!-- Tailwind CSS per il design con estensione dei colori -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'niki-viola': '#6A1B9A',  /* Colore viola principale dal logo */
                        'niki-fucsia': '#FF007F', /* Colore fucsia di accento */
                        'niki-azzurro': '#E0F7FA' /* Azzurro chiaro per sfondi */
                    }
                }
            }
        }
    </script>
    
    <!-- FontAwesome per le icone -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        /* Scorrimento fluido quando si clicca sul menu */
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- BARRA DI NAVIGAZIONE -->
    <nav class="bg-white shadow-md fixed w-full z-50 top-0">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <!-- Sostituisci src con il percorso del tuo logo img/logo.png se preferisci -->
                    <span class="font-bold text-2xl text-niki-viola">Lavasecco Niki</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#servizi" class="text-gray-600 hover:text-niki-fucsia font-medium">Servizi</a>
                    <a href="#recensioni" class="text-gray-600 hover:text-niki-fucsia font-medium">Recensioni</a>
                    <a href="#contatti" class="text-gray-600 hover:text-niki-fucsia font-medium">Contatti</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- SEZIONE HERO (Iniziale) -->
    <!-- Usa un'immagine o una sfumatura niki-azzurro come nell'insegna -->
    <header class="relative pt-16 flex items-center justify-center h-screen bg-cover bg-center" style="background-image: linear-gradient(rgba(224, 247, 250, 0.8), rgba(106, 27, 154, 0.2)), url('img/hero-bg.jpg');">
        <div class="text-center px-4">
            <!-- Puoi inserire qui il tuo logo reale image_0.png con tag <img> -->
            <img src="https://via.placeholder.com/300x150?text=Logo+Niki" alt="Logo Lavasecco Niki" class="mx-auto mb-6">
            
            <h1 class="text-5xl md:text-6xl font-bold mb-4 text-niki-viola">La cura perfetta per i tuoi capi</h1>
            <p class="text-xl md:text-2xl mb-8 text-gray-700">Lavanderia, Sartoria e molto altro a Cremona.</p>
            <a href="#contatti" class="bg-niki-fucsia hover:bg-magenta-700 text-white font-bold py-3 px-8 rounded-full transition duration-300">Vieni a trovarci</a>
        </div>
    </header>

    <!-- SEZIONE SERVIZI -->
    <section id="servizi" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-4xl font-bold text-niki-viola mb-12">I Nostri Servizi</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Servizio 1 -->
                <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition hover:border-niki-viola">
                    <i class="fas fa-tshirt text-4xl text-niki-fucsia mb-4"></i>
                    <h3 class="text-xl font-bold mb-2 text-niki-viola">Lavanderia e Lavasecco</h3>
                    <p class="text-gray-600">Pulizia profonda e delicata per ogni tipo di tessuto, dall'abbigliamento quotidiano ai capi eleganti.</p>
                </div>
                <!-- Servizio 2 -->
                <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition hover:border-niki-viola">
                    <i class="fas fa-bed text-4xl text-niki-fucsia mb-4"></i>
                    <h3 class="text-xl font-bold mb-2 text-niki-viola">Piumoni Sottovuoto</h3>
                    <p class="text-gray-600">Lavaggio accurato e confezionamento sottovuoto per risparmiare spazio nei tuoi armadi.</p>
                </div>
                <!-- Servizio 3 -->
                <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition hover:border-niki-viola">
                    <i class="fas fa-cut text-4xl text-niki-fucsia mb-4"></i>
                    <h3 class="text-xl font-bold mb-2 text-niki-viola">Riparazioni Sartoriali</h3>
                    <p class="text-gray-600">Orli, cambi zip, rammendi e creazioni sartoriali su misura per dare nuova vita ai tuoi abiti.</p>
                </div>
                <!-- Altri servizi... -->
            </div>
        </div>
    </section>

    <!-- GALLERIA -->
    <section class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold text-niki-viola mb-8">Il nostro lavoro</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <!-- Sostituisci src con i percorsi delle tue foto -->
                <img src="https://via.placeholder.com/300x200?text=Foto+Negozio+1" alt="Negozio" class="rounded-lg shadow-md w-full md:w-1/3 object-cover border-2 border-niki-viola">
                <img src="https://via.placeholder.com/300x200?text=Lavorazione+Capi" alt="Lavorazioni" class="rounded-lg shadow-md w-full md:w-1/3 object-cover border-2 border-niki-viola">
            </div>
        </div>
    </section>

    <!-- SEZIONE RECENSIONI -->
    <section id="recensioni" class="py-20 bg-niki-viola text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-4xl font-bold mb-12">Cosa dicono di noi</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div class="bg-niki-viola/80 p-6 rounded-xl border border-white/20">
                    <p class="italic text-lg">"Servizio impeccabile. Mi hanno salvato un vestito di seta macchiato, tornerò sicuramente!"</p>
                    <p class="mt-4 font-bold">- Maria R. <span class="text-niki-fucsia">★★★★★</span></p>
                </div>
                <div class="bg-niki-viola/80 p-6 rounded-xl border border-white/20">
                    <p class="italic text-lg">"Comodissimo il servizio di piumoni sottovuoto, e le ragazze della sartoria sono bravissime."</p>
                    <p class="mt-4 font-bold">- Luca F. <span class="text-niki-fucsia">★★★★★</span></p>
                </div>
            </div>
        </div>
    </section>

    <!-- DOVE SIAMO E CONTATTI -->
    <section id="contatti" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-niki-viola text-center mb-12">Vieni a trovarci</h2>
            
            <div class="flex flex-col lg:flex-row gap-12">
                <!-- Informazioni Contatto -->
                <div class="lg:w-1/3 space-y-6">
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-niki-viola"><i class="fas fa-map-marker-alt text-niki-fucsia mr-2"></i> Indirizzo</h3>
                        <p class="text-gray-600">Via Esempio, 123<br>26100 Cremona (CR)</p>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-niki-viola"><i class="fas fa-clock text-niki-fucsia mr-2"></i> Orari</h3>
                        <p class="text-gray-600">Lun - Ven: 08:30 - 12:30 / 15:00 - 19:00<br>Sabato: 08:30 - 12:30<br>Domenica: Chiuso</p>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-niki-viola"><i class="fas fa-phone text-niki-fucsia mr-2"></i> Contatti</h3>
                        <p class="text-gray-600 underline">Tel: 0372 123456</p>
                    </div>
                    <!-- Social personalizzati con colore niki-fucsia -->
                    <div class="pt-4 flex gap-4">
                        <a href="#" class="text-gray-400 hover:text-niki-fucsia text-3xl transition"><i class="fab fa-facebook"></i></a>
                        <a href="#" class="text-gray-400 hover:text-niki-fucsia text-3xl transition"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-400 hover:text-green-500 text-3xl transition"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>

                <!-- Mappa Google -->
                <div class="lg:w-2/3 h-80 rounded-xl overflow-hidden shadow-md border-4 border-niki-azzurro">
                    <!-- Sostituisci questo iframe con quello generato da Google Maps -->
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d45129.59367341857!2d9.976077399221598!3d45.136006096500364!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x478127bebfd48417%3A0x1d47153a817b7a66!2s26100%20Cremona%20CR!5e0!3m2!1sit!2sit!4v1700000000000!5m2!1sit!2sit" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-niki-viola text-gray-200 py-8 text-center">
        <p>&copy; 2026 Lavasecco Niki. Tutti i diritti riservati. P.IVA 12345678901</p>
        <p class="text-xs mt-2">Design personalizzato basato sulla vostra insegna</p>
    </footer>

</body>
</html>
