<!DOCTYPE html>
<html class="dark" lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Bem-vindo ao Hablo+</title>
  
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;900&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />

  <style type="text/tailwindcss">
    body {
      font-family: 'Inter', sans-serif;
    }
    .material-symbols-outlined {
      font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
    }
  </style>

  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#4A90E2",
            "background-light": "#F8F9FA",
            "background-dark": "#101922",
            "text-light-title": "#000000",
            "text-light-body": "#4A4A4A",
            "text-dark-title": "#FFFFFF",
            "text-dark-body": "#B0C4DE",
            "indicator-inactive-light": "#E0E0E0",
            "indicator-inactive-dark": "#324d67",
          },
          fontFamily: { "display": ["Inter", "sans-serif"] },
          borderRadius: { "DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px" },
        },
      },
    }
  </script>

  <style>
    body {
      min-height: max(884px, 100dvh);
    }
    
    /* Estilos para los puntos de paginación */
    .swiper-pagination-bullet {
      width: 8px;
      height: 8px;
      background-color: #E0E0E0; /* indicator-inactive-light */
      opacity: 1;
    }
    .dark .swiper-pagination-bullet {
      background-color: #324d67; /* indicator-inactive-dark */
    }
    
    /* Estilo para el punto activo */
    .swiper-pagination-bullet-active {
      background-color: #4A90E2; /* primary */
    }
  </style>
</head>

<body class="bg-background-light dark:bg-background-dark font-display">
  <div class="relative flex h-screen w-full flex-col group/design-root overflow-x-hidden">
    
    <header class="flex items-center p-4 pb-2 justify-between">
      <div class="flex size-12 shrink-0 items-center justify-start">
        </div>
      <div class="flex w-auto items-center justify-end">
        <a class="text-text-light-body dark:text-text-dark-body text-base font-bold leading-normal tracking-[0.015em] shrink-0 cursor-pointer" onclick="window.location.href='login.html'">Pular</a>
      </div>
    </header>

    <main class="flex-grow flex flex-col min-h-0">
      
      <div class="swiper h-full w-full">
        <div class="swiper-wrapper">
        
          <div class="swiper-slide flex h-full w-full flex-col gap-8 text-center items-center justify-center">
            <div class="w-48 h-48 sm:w-64 sm:h-64 flex items-center justify-center text-primary">
              <span class="material-symbols-outlined !text-9xl sm:!text-[12rem] text-primary">groups</span>
            </div>
            <div class="px-4">
              <h1 class="text-text-light-title dark:text-dark-title text-2xl font-bold leading-tight">Aulas ao Vivo com Professores Nativos</h1>
              <p class="text-text-light-body dark:text-text-dark-body text-base font-normal leading-normal mt-2">Interaja, pratique conversação em tempo real e receba feedback instantâneo.</p>
            </div>
          </div>

          <div class="swiper-slide flex h-full w-full flex-col gap-8 text-center items-center justify-center">
            <div class="w-48 h-48 sm:w-64 sm:h-64 flex items-center justify-center text-primary">
              <span class="material-symbols-outlined !text-9xl sm:!text-[12rem] text-primary">video_library</span>
            </div>
            <div class="px-4">
              <h1 class="text-text-light-title dark:text-dark-title text-2xl font-bold leading-tight">Aprenda no Seu Ritmo</h1>
              <p class="text-text-light-body dark:text-text-dark-body text-base font-normal leading-normal mt-2">Acesso ilimitado a aulas gravadas, exercícios e materiais de apoio a qualquer hora.</p>
            </div>
          </div>

          <div class="swiper-slide flex h-full w-full flex-col gap-8 text-center items-center justify-center">
            <div class="w-48 h-48 sm:w-64 sm:h-64 flex items-center justify-center text-primary">
              <span class="material-symbols-outlined !text-9xl sm:!text-[12rem] text-primary">workspace_premium</span>
            </div>
            <div class="px-4">
              <h1 class="text-text-light-title dark:text-dark-title text-2xl font-bold leading-tight">Receba seu Certificado de Conclusão</h1>
              <p class="text-text-light-body dark:text-text-dark-body text-base font-normal leading-normal mt-2">Valide suas novas habilidades linguísticas ao final de cada módulo.</p>
            </div>
          </div>

        </div>
      </div>
    </main>
      
    <footer class="p-4 pt-0 shrink-0">
      <div class="flex w-full flex-row items-center justify-center gap-3 py-5">
        <div class="swiper-pagination !relative !w-auto"></div>
      </div>

      <div class="flex py-3">
        <button onclick="window.location.href='login.html'" class="flex min-w-[84px] w-full max-w-[480px] mx-auto cursor-pointer items-center justify-center overflow-hidden rounded-lg h-12 px-5 flex-1 bg-primary text-white text-base font-bold leading-normal tracking-[0.015em] hover:bg-primary/90 focus:outline-none focus:ring-2 focus:ring-primary focus:ring-offset-2 focus:ring-offset-background-light dark:focus:ring-offset-background-dark">
          <span class="truncate">Começar</span>
        </button>
      </div>
    </footer>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

  <script>
    const swiper = new Swiper('.swiper', {
      // Queremos ver 1 slide a la vez
      slidesPerView: 1,
      // Permitir que el carrusel sea un bucle infinito
      loop: true,
      
      // Configuración de la paginación (los puntos)
      pagination: {
        el: '.swiper-pagination',
        // Permite hacer clic en los puntos para cambiar de slide
        clickable: true, 
      },
    });
  </script>
</body>
</html>
