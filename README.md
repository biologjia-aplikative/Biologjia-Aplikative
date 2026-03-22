<!DOCTYPE html>
<html lang="sq">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biologjia Aplikative - SHML SAHIT BAFTIU</title>

    <style>
        /* RREGULLIMET E PËRGJITHSHME */
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            background-color: #f4f6f9;
            line-height: 1.2; /* Zvogëlim i përgjithshëm i hapësirës */
        }

        /* HEADER DHE LOGO */
        header {
            background-color: #1e7f5c;
            color: white;
            padding: 15px 25px;
            display: flex;
            align-items: center;
            gap: 20px;
        }

        header img.logo {
            max-height: 80px;
            width: auto;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        header h1 {
            margin: 0;
            font-size: 28px;
            text-transform: uppercase;
        }

        header p {
            margin: 0;
            font-size: 15px;
            opacity: 0.9;
        }

        /* NAVIGIMI */
        nav {
            background-color: #145c43;
            padding: 12px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-weight: bold;
            font-size: 14px;
            transition: 0.3s;
        }

        nav a:hover { color: #a8e6cf; }

        /* SEKSIONET */
        section {
            padding: 20px 30px;
            margin: 20px auto;
            max-width: 1150px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        h2 {
            color: #1e7f5c;
            margin: 0 0 15px 0;
            border-bottom: 2px solid #1e7f5c;
            padding-bottom: 8px;
        }

        .permbajtja-flex {
            display: flex;
            flex-wrap: wrap;
            gap: 25px;
        }

        .kolona-mesimeve {
            flex: 2;
            min-width: 300px;
        }

        .kolona-shtese {
            flex: 1;
            min-width: 280px;
            background-color: #f9fbfb;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #1e7f5c;
            align-self: flex-start; /* E mban lart kolonën e djathtë */
        }

        /* RREGULLIMI I HAPËSIRAVE TË BRENDSHME */
        h3 {
            margin: 10px 0 2px 0; /* Zvogëlim i hapësirës mes titullit dhe butonit */
            font-size: 14px;
            color: #333;
            line-height: 1.1;
        }

        /* BUTONAT SHKARKO */
        .btn {
            background-color: #1e7f5c;
            color: white;
            padding: 3px 8px;
            border-radius: 4px;
            text-decoration: none;
            display: inline-block;
            font-size: 11px;
            font-weight: bold;
            margin-bottom: 8px;
            transition: 0.2s;
        }

        .btn:hover { background-color: #145c43; }

        /* KOLONA E DJATHTË - LINQET */
        .titull-shtese {
            font-size: 15px;
            font-weight: bold;
            color: #145c43;
            margin: 15px 0 8px 0;
            display: block;
            border-bottom: 1px dashed #ccc;
            padding-bottom: 3px;
        }

        .titull-shtese:first-child { margin-top: 0; }

        .link-shtese {
            display: block;
            color: #444;
            text-decoration: none;
            font-size: 13px;
            padding: 4px 0;
            transition: 0.2s;
        }

        .link-shtese:hover { color: #1e7f5c; padding-left: 5px; }

        footer {
            background-color: #1e7f5c;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <img src="logo_shkolles.jpg" alt="Logo SHML Sahit Baftiu" class="logo">
    <div>
        <h1>SHML SAHIT BAFTIU</h1>
        <p>Platformë mësimore - Biologjia Aplikative</p>
    </div>
</header>

<nav>
    <a href="#klasa10">Klasa 10</a>
    <a href="#klasa11">Klasa 11</a>
    <a href="#klasa12">Klasa 12</a>
    <a href="#fiziologjia">Fiziologjia</a>
    <a href="#mjedisi">Mjedisi Jetësor</a>
</nav>

<section id="klasa10">
    <h2>Klasa 10</h2>
    <div class="permbajtja-flex">
        <div class="kolona-mesimeve">
            <h3>0. BIOLOGJIA 10 Libri</h3>
            <a href="materiale/Klasa%2010/0.%20BIOLOGJIA%2010%20Libri.pdf" class="btn" download>Shkarko Prezantimin</a>
            
            <h3>1. Qeliza dhe përbërja kimike e saj</h3>
            <a href="materiale/Klasa%2010/1%20Qeliza%20dhe%20përbërja%20kimike%20e%20saj.ppt" class="btn" download>Shkarko Prezantimin</a>
            
            <h3>2. PARAQITJA E JETËS NË TOKË</h3>
            <a href="materiale/Klasa%2010/2%20PARAQITJA%20E%20JETËS%20NË%20TOKË.ppt" class="btn" download>Shkarko Prezantimin</a>
            
            <h3>3. ORGANELET QELIZORE 1</h3>
            <a href="materiale/Klasa%2010/3.%20ORGANELET%20QELIZORE%201.ppt" class="btn" download>Shkarko Prezantimin</a>

            <h3>4. ORGANELET QELIZORE 2</h3>
            <a href="materiale/Klasa%2010/4.%20ORGANELET%20QELIZORE%202.ppt" class="btn" download>Shkarko Prezantimin</a>

            <h3>5. Krahasimi i qelizave</h3>
            <a href="materiale/Klasa%2010/5.%20Krahasimi%20i%20qelizave.ppt" class="btn" download>Shkarko Prezantimin</a>

            <h3>6. CIKLI JETЁSOR I QELIZЁS, MITOZA-MEJOZA</h3>
            <a href="materiale/Klasa%2010/6.%20CIKLI%20JETЁSOR%20I%20QELIZЁS,%20MITOZA-MEJOZA.ppt" class="btn" download>Shkarko Prezantimin</a>

            <h3>7. METABOLIZMI QELIZOR</h3>
            <a href="materiale/Klasa%2010/7.%20METABOLIZMI%20QELIZOR.ppt" class="btn" download>Shkarko Prezantimin</a>
        </div>

        <div class="kolona-shtese">
            <span class="titull-shtese">📂 Planprogramet - Klasa 10</span>
            <a href="materiale/Klasa%2010/Planprogramet/Plani%20vjetor.doc" class="link-shtese" download>📄 Plani vjetor (Word)</a>
            <a href="materiale/Klasa%2010/Planprogramet/Plani%20mujor%20-%20Shtator-Qershor.doc" class="link-shtese" download>📄 Plani mujor</a>
            <a href="materiale/Klasa%2010/Planprogramet/Fletore%20pune%20Biologjia%2010.pdf" class="link-shtese" download>📕 Fletore pune 10</a>
            <a href="materiale/Klasa%2010/Planprogramet/Praktikum%20i%20Biologjise%20X.pdf" class="link-shtese" download>🧪 Praktikum i Biologjisë X</a>
            
            <span class="titull-shtese">🎥 Videoprezentime</span>
            <a href="#" class="link-shtese">▶️ Video: Ndërtimi i Qelizës</a>
            <a href="#" class="link-shtese">▶️ Video: Mikroskopi</a>
        </div>
    </div>
</section>

<section id="klasa11">
    <h2>Klasa 11</h2>
    <div class="permbajtja-flex">
        <div class="kolona-mesimeve">
            <h3>0. BIOLOGJIA 11</h3>
            <a href="materiale/Klasa%2011/0.%20BIOLOGJIA%2011.pdf" class="btn" download>Shkarko Prezantimin</a>
            
            <h3>1. KARAKTERISTIKAT E PESË MBRETËRIVE</h3>
            <a href="materiale/Klasa%2011/1.%20KARAKTERISTIKAT%20E%20PESË%20MBRETËRIVE.ppt" class="btn" download>Shkarko Prezantimin</a>
            
            <h3>2. BAKTERIET</h3>
            <a href="materiale/Klasa%2011/2.%20BAKTERIET.ppt" class="btn" download>Shkarko Prezantimin</a>
        </div>

        <div class="kolona-shtese">
            <span class="titull-shtese">📂 Planprogramet - Klasa 11</span>
            <a href="materiale/Klasa%2011/Planprogramet/Plani%20vjetor.doc" class="link-shtese" download>📄 Plani vjetor (Word)</a>
            <a href="materiale/Klasa%2011/Planprogramet/Plani%20mujor%20-%20Shtator-Qershor.doc" class="link-shtese" download>📄 Plani mujor</a>
            <a href="materiale/Klasa%2011/Planprogramet/Fletore%20pune%20Biologjia%2011.pdf" class="link-shtese" download>📕 Fletore pune 11</a>
        </div>
    </div>
</section>

<section id="klasa12">
    <h2>Klasa 12</h2>
    <div class="permbajtja-flex">
        <div class="kolona-mesimeve">
            <h3>0. Biologjia 12</h3>
            <a href="materiale/Klasa%2012/0.%20Biologjia.pdf" class="btn" download>Shkarko Prezantimin</a>
            
            <h3>1. Biokimia</h3>
            <a href="materiale/Klasa%2012/1.%20Biokimia.ppt" class="btn" download>Shkarko Prezantimin</a>
        </div>

        <div class="kolona-shtese">
            <span class="titull-shtese">📂 Planprogramet - Klasa 12</span>
            <a href="materiale/Klasa%2012/Planprogramet/Plani%20vjetor.doc" class="link-shtese" download>📄 Plani vjetor</a>
            <a href="materiale/Klasa%2012/Planprogramet/Praktikum%20i%20Biokimisë.doc" class="link-shtese" download>🧪 Praktikum i Biokimisë</a>
        </div>
    </div>
</section>

<section id="fiziologjia">
    <h2>Fiziologjia e shtazeve dhe njeriut</h2>
    <div class="permbajtja-flex">
        <div class="kolona-mesimeve">
            <h3>0. Fiziologji e shtazeve dhe njeriut</h3>
            <a href="materiale/Fiziologjia%20e%20shtazeve%20dhe%20njeriut/0.%20Fiziologji%20e%20shtazeve%20dhe%20njeriut.pdf" class="btn" download>Shkarko Prezantimin</a>
            <h3>1. QELIZA DHE ORGANELET E SAJ</h3>
            <a href="materiale/Fiziologjia%20e%20shtazeve%20dhe%20njeriut/1.%20QELIZA%20DHE%20ORGANELET%20E%20SAJ.ppt" class="btn" download>Shkarko Prezantimin</a>
        </div>

        <div class="kolona-shtese">
            <span class="titull-shtese">📂 Planprogramet - Fiziologjia</span>
            <a href="materiale/Fiziologjia%20e%20shtazeve%20dhe%20njeriut/Planprogramet/Plani%20vjetor.doc" class="link-shtese" download>📄 Plani vjetor</a>
            <a href="materiale/Fiziologjia%20e%20shtazeve%20dhe%20njeriut/Planprogramet/Fletore%20pune%20Fiziologjia.pdf" class="link-shtese" download>📕 Fletore pune</a>
        </div>
    </div>
</section>

<section id="mjedisi">
    <h2>Biologji e mjedisit jetësor</h2>
    <div class="permbajtja-flex">
        <div class="kolona-mesimeve">
            <h3>0. BIOLOGJI E MJEDISIT JETËSOR</h3>
            <a href="materiale/Biologji%20e%20mjedisit%20jetësor/0.%20BIOLOGJI%20E%20MJEDISIT%20JETËSOR.pdf" class="btn" download>Shkarko Prezantimin</a>
        </div>

        <div class="kolona-shtese">
            <span class="titull-shtese">📂 Planprogramet - Mjedisi</span>
            <a href="materiale/Biologji%20e%20mjedisit%20jetësor/Planprogramet/Plani%20vjetor.doc" class="link-shtese" download>📄 Plani vjetor</a>
        </div>
    </div>
</section>

<footer>
    © 2026 SHML SAHIT BAFTIU | Gjilan <br>
    Të gjitha të drejtat e rezervuara.
</footer>

</body>
</html>
