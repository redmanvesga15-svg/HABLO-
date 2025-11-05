<!DOCTYPE html>
<html class="dark" lang="pt">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Hablo+ Splash Screen</title>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#4A90E2", // Vibrant Blue
            "secondary": "#50E3C2", // Energetic Green
            "background-light": "#F8F9FA", // Off-white
            "background-dark": "#101922",
          },
          fontFamily: {
            "display": ["Inter", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
  <style>
    .material-symbols-outlined {
      font-variation-settings:
        'FILL' 0,
        'wght' 400,
        'GRAD' 0,
        'opsz' 24
    }

    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>

<body class="font-display">
  <div class="relative flex h-[100svh] w-full flex-col bg-background-light dark:bg-background-dark group/design-root overflow-x-hidden">
    <div class="flex flex-1 flex-col items-center justify-center p-8">
      <div class="flex flex-col items-center justify-center gap-4">
        <div class="relative flex h-auto w-40 flex-col aspect-square">
          <div class="w-full bg-center bg-no-repeat bg-cover aspect-auto rounded-none flex-1" data-alt="Hablo+ app logo, a stylized plus sign combining blue and green colors" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBPXOzWR2J6-BKVcjlY0Y9AsPiXDXRDdetIfuYezlJiE6y_Jjlf8EwPup6qZgdb8Ljty8nh7TMt0UnBpJJJcGR42oqlVKO3-PGrS4DdJgk12ImqoojIyf0Z8OsyFynqWrQ7u9olqrr9WFYsBdAy3JpIUVAw_w9cUFgJJRtXEVgZJQn5KwEjRe4r9Kp7-cLMN12ZUBd0YRFTHbbECuIcmm7PI4EDkLKr4cjJXFDppqzpaezsN-DhI9i9p32HIeWY7jk6K1eATBZPL3ND");'></div>
        </div>
        <div class="text-center">
          <h3 class="text-black dark:text-white tracking-light text-2xl font-bold leading-tight">Fale com o mundo</h3>
        </div>
      </div>
    </div>
    <div class="w-full px-8 pb-12">
      <div class="flex flex-col gap-3">
        <div class="rounded-full bg-primary/20 dark:bg-white/10">
          <div class="h-2 rounded-full bg-primary" style="width: 45%;"></div>
        </div>
      </div>
    </div>
  </div><!DOCTYPE html>
<html class="dark" lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Bem-vindo ao Hablo+</title>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;900&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
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
            "primary": "#4A90E2", // From user prompt
            "background-light": "#F8F9FA", // From user prompt
            "background-dark": "#101922", // Modified for better contrast
            "text-light-title": "#000000",
            "text-light-body": "#4A4A4A",
            "text-dark-title": "#FFFFFF",
            "text-dark-body": "#B0C4DE",
            "indicator-inactive-light": "#E0E0E0",
            "indicator-inactive-dark": "#324d67",
          },
          fontFamily: {
            "display": ["Inter", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
  <style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>

<body class="bg-background-light dark:bg-background-dark font-display">
  <div class="relative flex h-auto min-h-screen w-full flex-col group/design-root overflow-x-hidden">
    <header class="flex items-center p-4 pb-2 justify-between">
      <div class="flex size-12 shrink-0 items-center justify-start">
        </div>
      <div class="flex w-auto items-center justify-end">
        <a class="text-text-light-body dark:text-text-dark-body text-base font-bold leading-normal tracking-[0.015em] shrink-0" href="#">Pular</a>
      </div>
    </header>
    <main class="flex-grow flex flex-col">
      <div class="flex-grow flex overflow-x-auto [-ms-scrollbar-style:none] [scrollbar-width:none] [&::-webkit-scrollbar]:hidden">
        <div class="flex items-center p-4 gap-4 w-full">
          <div class="flex h-full w-full flex-shrink-0 flex-col gap-8 rounded-lg text-center items-center justify-center">
            <div class="w-48 h-48 sm:w-64 sm:h-64 flex items-center justify-center text-primary">
              <span class="material-symbols-outlined !text-9xl sm:!text-[12rem] text-primary">groups</span>
            </div>
            <div class="px-4">
              <h1 class="text-text-light-title dark:text-dark-title text-2xl font-bold leading-tight">Aulas ao Vivo com Professores Nativos</h1>
              <p class="text-text-light-body dark:text-text-dark-body text-base font-normal leading-normal mt-2">Interaja, pratique conversação em tempo real e receba feedback instantâneo.</p>
            </div>
          </div>
          <div class="flex h-full w-full flex-shrink-0 flex-col gap-8 rounded-lg text-center items-center justify-center">
            <div class="w-48 h-48 sm:w-64 sm:h-64 flex items-center justify-center text-primary">
              <span class="material-symbols-outlined !text-9xl sm:!text-[12rem] text-primary">video_library</span>
            </div>
            <div class="px-4">
              <h1 class="text-text-light-title dark:text-dark-title text-2xl font-bold leading-tight">Aprenda no Seu Ritmo</h1>
              <p class="text-text-light-body dark:text-text-dark-body text-base font-normal leading-normal mt-2">Acesso ilimitado a aulas gravadas, exercícios e materiais de apoio a qualquer hora.</p>
            </div>
          </div>
          <div class="flex h-full w-full flex-shrink-0 flex-col gap-8 rounded-lg text-center items-center justify-center">
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
      <footer class="p-4 pt-0">
        <div class="flex w-full flex-row items-center justify-center gap-3 py-5">
          <div class="h-2 w-2 rounded-full bg-primary"></div>
          <div class="h-2 w-2 rounded-full bg-indicator-inactive-light dark:bg-indicator-inactive-dark"></div>
          <div class="h-2 w-2 rounded-full bg-indicator-inactive-light dark:bg-indicator-inactive-dark"></div>
        </div>
        <div class="flex py-3">
          <button class="flex min-w-[84px] w-full max-w-[480px] mx-auto cursor-pointer items-center justify-center overflow-hidden rounded-lg h-12 px-5 flex-1 bg-primary text-white text-base font-bold leading-normal tracking-[0.015em] hover:bg-primary/90 focus:outline-none focus:ring-2 focus:ring-primary focus:ring-offset-2 focus:ring-offset-background-light dark:focus:ring-offset-background-dark">
            <span class="truncate">Começar</span>
          </button>
        </div>
      </footer>
    </main>
  </div>
</body>
</html><!DOCTYPE html>
<html class="" lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Login | DuoLingo</title>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#1985f0",
            "background-light": "#f6f7f8",
            "background-dark": "#101922",
          },
          fontFamily: {
            "display": ["Inter", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
  <style>
    .material-symbols-outlined {
      font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
    }

    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>

<body class="font-display">
  <div class="relative flex min-h-screen w-full flex-col items-center justify-center bg-background-light dark:bg-background-dark p-4">
    <div class="w-full max-w-sm">
      <div class="mb-6 flex justify-center">
        <div class="flex h-10 w-48 items-center justify-center rounded-lg bg-gray-200 dark:bg-black/20 p-1">
          <label class="flex h-full grow cursor-pointer items-center justify-center overflow-hidden rounded-md px-2 text-sm font-medium leading-normal text-gray-500 has-[:checked]:bg-white has-[:checked]:text-gray-900 dark:text-gray-400 has-[:checked]:dark:bg-background-dark has-[:checked]:dark:text-white">
            <span class="truncate">Português</span>
            <input checked="" class="invisible w-0" name="language-selector" type="radio" value="Português" />
          </label>
          <label class="flex h-full grow cursor-pointer items-center justify-center overflow-hidden rounded-md px-2 text-sm font-medium leading-normal text-gray-500 has-[:checked]:bg-white has-[:checked]:text-gray-900 dark:text-gray-400 has-[:checked]:dark:bg-background-dark has-[:checked]:dark:text-white">
            <span class="truncate">Español</span>
            <input class="invisible w-0" name="language-selector" type="radio" value="Español" />
          </label>
        </div>
      </div>
      <div class="mb-4 flex justify-center">
        <div class="flex h-16 w-16 items-center justify-center rounded-full bg-primary/20">
          <span class="material-symbols-outlined text-4xl text-primary">translate</span>
        </div>
      </div>
      <h1 class="text-center text-[32px] font-bold leading-tight tracking-tight text-gray-900 dark:text-white">Bem-vindo!</h1>
      <p class="pt-1 pb-8 text-center text-base font-normal leading-normal text-gray-600 dark:text-gray-400">Vamos começar sua jornada</p>
      <div class="flex w-full flex-col gap-4">
        <label class="flex flex-col">
          <p class="pb-2 text-sm font-medium text-gray-700 dark:text-gray-300">E-mail ou Telefone</p>
          <div class="relative flex items-center">
            <span class="material-symbols-outlined absolute left-3 text-gray-400 dark:text-gray-500">person</span>
            <input class="form-input h-12 w-full flex-1 resize-none overflow-hidden rounded-lg border border-gray-300 bg-white p-3 pl-10 text-base font-normal leading-normal text-gray-900 placeholder:text-gray-400 focus:border-primary focus:outline-0 focus:ring-2 focus:ring-primary/50 dark:border-gray-700 dark:bg-background-dark dark:text-white dark:placeholder:text-gray-500 dark:focus:border-primary" placeholder="Digite seu e-mail ou telefone" value="" />
          </div>
        </label>
        <label class="flex flex-col">
          <p class="pb-2 text-sm font-medium text-gray-700 dark:text-gray-300">Senha</p>
          <div class="relative flex items-center">
            <span class="material-symbols-outlined absolute left-3 text-gray-400 dark:text-gray-500">lock</span>
            <input class="form-input h-12 w-full flex-1 resize-none overflow-hidden rounded-lg border border-gray-300 bg-white p-3 pl-10 text-base font-normal leading-normal text-gray-900 placeholder:text-gray-400 focus:border-primary focus:outline-0 focus:ring-2 focus:ring-primary/50 dark:border-gray-700 dark:bg-background-dark dark:text-white dark:placeholder:text-gray-500 dark:focus:border-primary" placeholder="Digite sua senha" type="password" value="" />
          </div>
        </label>
        <div class="text-right">
          <a class="text-sm font-medium text-primary hover:underline" href="#">Esqueci minha senha</a>
        </div>
      </div>
      <div class="mt-6 flex flex-col gap-3">
        <button class="flex h-12 w-full items-center justify-center rounded-lg bg-primary px-4 text-base font-semibold text-white transition-colors hover:bg-primary/90">Entrar</button>
        <button class="flex h-12 w-full items-center justify-center rounded-lg border border-gray-300 bg-white px-4 text-base font-semibold text-gray-800 transition-colors hover:bg-gray-50 dark:border-gray-700 dark:bg-white/5 dark:text-white dark:hover:bg-white/10">Cadastrar</button>
      </div>
      <div class="relative my-6 flex items-center justify-center">
        <div class="absolute w-full border-t border-gray-300 dark:border-gray-700"></div>
        <span class="relative bg-background-light px-2 text-sm text-gray-500 dark:bg-background-dark dark:text-gray-400">OU</span>
      </div>
      <div class="flex flex-col gap-3">
        <button class="flex h-12 w-full items-center justify-center gap-3 rounded-lg border border-gray-300 bg-white px-4 text-base font-medium text-gray-700 transition-colors hover:bg-gray-50 dark:border-gray-700 dark:bg-transparent dark:text-white dark:hover:bg-white/5">
          <img class="h-5 w-5" data-alt="Google logo" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCT3-n9mPGp9C9Pw9Z-JQOfOrkQoRn8cKx5NyKzziZZ2_afHbAtTFrLOhtiGD9Gax2CWppATn-cs_fvccIq6Dt-PAcPL5qXzSfCGChncGwieBnKXrPWOMzsZq6iRvpzdyD077x2o8CMnGd4UpifmB428qzpGWec1Gf5kQwPpg2mDrdeWyk6o0M1ZcsziRxJqZ-_3NbAgV-mEhWF40oKazcPBIApdPXygglcxiuAjGgJF-3v8XnEAUGXes1tRIxkdFWjRVD-_d0Qg2ZD" />
          Continuar com Google
        </button>
        <button class="flex h-12 w-full items-center justify-center gap-3 rounded-lg border border-gray-300 bg-black px-4 text-base font-medium text-white transition-colors hover:bg-gray-800 dark:border-gray-700 dark:bg-white dark:text-black dark:hover:bg-gray-200">
          <img class="h-5 w-5 dark:invert" data-alt="Apple logo" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1TZbJM93mmMJH8rekW-z9bLD5P8Ko5RptN6OgnEiZri9Zn7XJoG9ITHYjNFKb10_584r7hE1yE--VD3a4TSrEIIE-iSKlle3ZVnkI0GXcvJPMo4xIFWPFu1uMd9t0k8aWUQnM8QnX_hMBA8PadOff9BgVerVthyKTi-xjS6YkB-c30KolLDdpnHeGsqOygISjsHrIwrqpJIVVM_XXndgYhAdytu6RbN8FqCQ_zWWcmCPthyKLIA1XN7_3qfK92HBg2tgdw0qID3Ic" />
          Continuar com Apple
        </button>
        <button class="flex h-12 w-full items-center justify-center gap-3 rounded-lg border border-transparent bg-[#1877F2] px-4 text-base font-medium text-white transition-colors hover:bg-[#166fe5]">
          <img class="h-5 w-5" data-alt="Facebook logo" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDODzaiOXnJhyq2bWKoX3BPscEH_vrgBf_b-38u4raYgbyJbJIWKxVklkJ-4QQ-2ob_fO6KIr1CLTCNx2RjsIaocjym3cMRfMRAdX_uz2uxr4-V8Gn8PIh1AFiuKcfH_lZ5jpenUbNCuldx-VlTYs1ZgD7hLh3J23_iXQvNL2p8If3QxbxFMsIfLp-6WOp4CX5NFAERyCmqtuJ1B3PKSdu7nLwes3WkT4902m3Zpi4frXmZNns20eDbJPWyk3GyLR0ZQayBCS6eN0zP" />
          Continuar com Facebook
        </button>
      </div>
      <div class="mt-8 text-center">
        <p class="text-sm text-gray-600 dark:text-gray-400">
          Ao continuar, você concorda com nossos
          <a class="font-medium text-primary hover:underline" href="#">Termos de Serviço</a> e <a class="font-medium text-primary hover:underline" href="#">Política de Privacidade</a>.
        </p>
        <p class="mt-4 text-sm text-gray-600 dark:text-gray-400">
          Não tem uma conta? <a class="font-bold text-primary hover:underline" href="#">Cadastre-se</a>
        </p>
      </div>
    </div>
  </div>
</body>
</html><!DOCTYPE html>
<html class="dark" lang="pt">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Hablo+ Subscription</title>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#4A90E2", // Vibrant Blue
            "secondary": "#50E3C2", // Energetic Green
            "background-light": "#F8F9FA", // Off-white
            "background-dark": "#101922",
          },
          fontFamily: {
            "display": ["Inter", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
  <style>
    .material-symbols-outlined {
      font-variation-settings: 'FILL' 1, 'wght' 400, 'GRAD' 0, 'opsz' 24
    }

    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>

<body class="font-display">
  <div class="relative flex h-full min-h-screen w-full flex-col bg-background-light dark:bg-background-dark group/design-root overflow-x-hidden">
    <header class="flex h-14 shrink-0 items-center justify-between px-4">
      <button class="flex items-center justify-center p-2 text-black dark:text-white">
        <span class="material-symbols-outlined">arrow_back</span>
      </button>
      <h1 class="text-lg font-semibold text-black dark:text-white">Assinatura</h1>
      <div class="w-9"></div>
    </header>
    <main class="flex-1 overflow-y-auto p-6">
      <div class="flex flex-col gap-8">
        <div class="rounded-xl border border-gray-200 bg-white p-6 text-center dark:border-gray-700 dark:bg-gray-800">
          <h2 class="text-2xl font-bold text-black dark:text-white">Plano Mensal</h2>
          <p class="mt-2 text-4xl font-bold text-primary">R$20<span class="text-base font-normal text-gray-500 dark:text-gray-400">/mês</span></p>
          <p class="mt-4 rounded-lg bg-secondary/20 p-2 text-sm text-secondary-800 dark:text-secondary">Comece com um teste gratuito de 7 dias</p>
        </div>
        <div>
          <h3 class="text-lg font-semibold text-black dark:text-white">Recursos incluídos:</h3>
          <ul class="mt-4 space-y-3">
            <li class="flex items-center gap-3">
              <span class="material-symbols-outlined text-secondary">check_circle</span>
              <span class="text-gray-700 dark:text-gray-300">Acesso ilimitado a todas as lições</span>
            </li>
            <li class="flex items-center gap-3">
              <span class="material-symbols-outlined text-secondary">check_circle</span>
              <span class="text-gray-700 dark:text-gray-300">Aulas com falantes nativos</span>
            </li>
            <li class="flex items-center gap-3">
              <span class="material-symbols-outlined text-secondary">check_circle</span>
              <span class="text-gray-700 dark:text-gray-300">Exercícios interativos e quizzes</span>
            </li>
            <li class="flex items-center gap-3">
              <span class="material-symbols-outlined text-secondary">check_circle</span>
              <span class="text-gray-700 dark:text-gray-300">Experiência sem anúncios</span>
            </li>
          </ul>
        </div>
        <div>
          <h3 class="text-lg font-semibold text-black dark:text-white">Opções de Pagamento</h3>
          <div class="mt-4 space-y-4">
            <div class="rounded-lg border border-gray-200 bg-white p-4 dark:border-gray-700 dark:bg-gray-800">
              <div class="flex items-center justify-between">
                <div class="flex items-center gap-3">
                  <div class="flex h-10 w-10 items-center justify-center rounded-lg bg-gray-100 dark:bg-gray-700">
                    <svg class="h-6 w-6 text-black dark:text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                      <path d="M12 4v16m8-8H4" stroke-linecap="round" stroke-linejoin="round"></path>
                      <path d="M15 4l-6 6m0 4l6 6" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg>
                  </div>
                  <span class="font-medium text-black dark:text-white">PIX</span>
                </div>
                <button class="text-sm font-semibold text-primary">Selecionar</button>
              </div>
              <div class="mt-4 rounded-md bg-gray-100 p-3 text-center dark:bg-gray-700">
                <p class="text-sm text-gray-500 dark:text-gray-400">Chave PIX (Telefone)</p>
                <p class="font-mono text-base font-medium text-black dark:text-white">15930338426</p>
              </div>
            </div>
            <button class="flex w-full items-center justify-between rounded-lg border border-gray-200 bg-white p-4 text-left dark:border-gray-700 dark:bg-gray-800">
              <div class="flex items-center gap-3">
                <div class="flex h-10 w-10 items-center justify-center rounded-lg bg-gray-100 dark:bg-gray-700">
                  <span class="material-symbols-outlined text-black dark:text-white">credit_card</span>
                </div>
                <span class="font-medium text-black dark:text-white">Cartão de Crédito</span>
              </div>
              <span class="material-symbols-outlined text-gray-400 dark:text-gray-500">chevron_right</span>
            </button>
            <button class="flex w-full items-center justify-between rounded-lg border border-gray-200 bg-white p-4 text-left dark:border-gray-700 dark:bg-gray-800">
              <div class="flex items-center gap-3">
                <div class="flex h-10 w-10 items-center justify-center rounded-lg bg-gray-100 dark:bg-gray-700">
                  <span class="material-symbols-outlined text-black dark:text-white">storefront</span>
                </div>
                <span class="font-medium text-black dark:text-white">Pagar com a Loja</span>
              </div>
              <span class="material-symbols-outlined text-gray-400 dark:text-gray-500">chevron_right</span>
            </button>
          </div>
        </div>
      </div>
    </main>
    <footer class="w-full shrink-0 p-6">
      <button class="w-full rounded-full bg-primary py-4 text-center text-lg font-bold text-white shadow-lg shadow-primary/30 transition-colors hover:bg-primary/90">
        Continuar com Teste Gratuito
      </button>
      <p class="mt-4 text-center text-xs text-gray-500 dark:text-gray-400">Após 7 dias, a assinatura de R$20/mês começará. Cancele a qualquer momento.</p>
    </footer>
  </div>
</body>
</html><!DOCTYPE html>
<html class="dark" lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Pagamento com PIX</title>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com" rel="preconnect" />
  <link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#1985f0",
            "background-light": "#f6f7f8",
            "background-dark": "#101922",
          },
          fontFamily: {
            "display": ["Inter", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
  <style>
    body {
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      min-height: max(884px, 100dvh);
    }
  </style>
</head>

<body class="bg-background-light dark:bg-background-dark font-display">
  <div class="flex min-h-screen w-full flex-col">
    <header class="flex shrink-0 items-center bg-background-light dark:bg-background-dark p-4">
      <button class="flex h-10 w-10 shrink-0 items-center justify-center rounded-full text-zinc-700 dark:text-zinc-300">
        <span class="material-symbols-outlined text-2xl">arrow_back</span>
      </button>
      <h1 class="flex-1 text-center text-lg font-bold text-zinc-900 dark:text-white">Pagamento com PIX</h1>
      <div class="w-10 shrink-0"></div>
    </header>
    <main class="flex flex-1 flex-col items-center px-4 pb-8 pt-2">
      <div class="flex w-full max-w-sm flex-col items-center">
        <h2 class="px-4 pb-1 pt-4 text-center text-2xl font-bold leading-tight tracking-tight text-zinc-900 dark:text-white">Escaneie o código para pagar</h2>
        <div class="mt-4 flex w-full max-w-[240px] grow items-center justify-center rounded-xl border border-zinc-200 bg-white p-4 dark:border-zinc-700">
          <img class="aspect-square w-full" data-alt="QR Code para pagamento via PIX" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCf1It76Wdu_9MSovTkowDkBk7f1BBnHAbFsYTlqgEk9WWAPTayRix2ZdPQ-_fINTk32lPF0POHzzRzjoKCqZS1QkF3BkWFMlN-IsmCDPPLAZ9alCksFpyM-1Wtgzz6Bz2u6nefdt8DEg86UrzFK5fOpYyoysGns_OMzpp3wMxhNvYNsJabhs2RSduIQhCI54OBYwr8KTwVoBMbHiGCybOjy4Jcl-52cfFHdnyfGMSxtVRskFvVPZARFjbuZpMX4CZ4yUhPGYvI_-35" />
        </div>
        <div class="mt-6 flex flex-col items-center">
          <p class="text-center text-sm font-normal text-zinc-600 dark:text-zinc-400">Este código expira em:</p>
          <p class="mt-1 text-lg font-bold text-orange-500 dark:text-orange-400">14:59</p>
        </div>
        <div class="mt-6 w-full rounded-xl border border-zinc-200 bg-zinc-100 p-4 dark:border-zinc-700 dark:bg-zinc-800/50">
          <p class="text-sm font-medium text-zinc-600 dark:text-zinc-400">Chave PIX (Copia e Cola)</p>
          <div class="mt-2 flex items-center justify-between gap-4">
            <p class="truncate font-mono text-base font-semibold text-zinc-800 dark:text-zinc-200">15930338426</p>
            <button class="flex shrink-0 items-center gap-2 rounded-lg bg-primary/20 px-3 py-2 text-sm font-semibold text-primary dark:bg-primary/30">
              <span class="material-symbols-outlined text-base">content_copy</span>
              Copiar
            </button>
          </div>
        </div>
        <div class="mt-4 w-full rounded-xl p-4">
          <div class="flex items-baseline justify-between">
            <span class="text-base font-medium text-zinc-600 dark:text-zinc-400">Total a pagar:</span>
            <span class="text-2xl font-bold text-zinc-900 dark:text-white">R$ 49,90</span>
          </div>
        </div>
        <div class="mt-4 w-full text-left">
          <ol class="space-y-3 text-sm text-zinc-600 dark:text-zinc-400">
            <li class="flex items-start gap-3">
              <span class="flex h-5 w-5 shrink-0 items-center justify-center rounded-full bg-zinc-200 text-xs font-bold text-zinc-700 dark:bg-zinc-700 dark:text-zinc-200">1</span>
              <span>Copie a chave ou escaneie o QR Code acima.</span>
            </li>
            <li class="flex items-start gap-3">
              <span class="flex h-5 w-5 shrink-0 items-center justify-center rounded-full bg-zinc-200 text-xs font-bold text-zinc-700 dark:bg-zinc-700 dark:text-zinc-200">2</span>
              <span>Abra o app do seu banco e faça o pagamento.</span>
            </li>
            <li class="flex items-start gap-3">
              <span class="flex h-5 w-5 shrink-0 items-center justify-center rounded-full bg-zinc-200 text-xs font-bold text-zinc-700 dark:bg-zinc-700 dark:text-zinc-200">3</span>
              <span>Volte aqui e clique no botão abaixo para confirmar.</span>
            </li>
          </ol>
        </div>
      </div>
    </main>
    <footer class="sticky bottom-0 mt-auto w-full border-t border-zinc-200 bg-background-light/80 p-4 backdrop-blur-sm dark:border-zinc-800 dark:bg-background-dark/80">
      <div class="mx-auto flex w-full max-w-sm flex-col items-center">
        <button class="h-12 w-full rounded-xl bg-primary px-6 text-base font-semibold text-white shadow-sm transition-colors hover:bg-primary/90">
          Já paguei, confirmar
        </button>
        <button class="mt-3 h-10 w-full rounded-xl px-6 text-sm font-medium text-zinc-600 transition-colors hover:bg-zinc-200 dark:text-zinc-400 dark:hover:bg-zinc-800">
          Cancelar pedido
        </button>
      </div>
    </footer>
  </div>
</body>
</html><!DOCTYPE html>
<html class="dark" lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Confirmação de Pagamento</title>
  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  <link href="https://fonts.googleapis.com" rel="preconnect" />
  <link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
  <script>
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#1985f0",
            "background-light": "#f6f7f8",
            "background-dark": "#101922",
            "success": "#28a745"
          },
          fontFamily: {
            "display": ["Inter", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
  <style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>

<body class="bg-background-light dark:bg-background-dark font-display">
  <div class="relative flex h-auto min-h-screen w-full flex-col bg-background-light dark:bg-background-dark">
    <div class="flex items-center p-4">
      <div class="text-slate-800 dark:text-white flex size-12 shrink-0 items-center justify-start">
        <span class="material-symbols-outlined text-2xl">arrow_back</span>
      </div>
      <h2 class="text-slate-900 dark:text-white text-lg font-bold leading-tight tracking-[-0.015em] flex-1 text-center pr-12">Pagamento</h2>
    </div>
    <div class="flex flex-col items-center justify-center p-4 flex-grow">
      <div class="w-24 h-24 rounded-full bg-success/20 dark:bg-success/30 flex items-center justify-center mb-6">
        <div class="w-16 h-16 rounded-full bg-success flex items-center justify-center">
          <span class="material-symbols-outlined text-white text-5xl">check</span>
        </div>
      </div>
      <h1 class="text-slate-900 dark:text-white tracking-light text-[32px] font-bold leading-tight text-center pb-2">Assinatura Ativada!</h1>
      <p class="text-slate-600 dark:text-slate-300 text-base font-normal leading-normal pb-8 text-center max-w-sm">Parabéns! Você agora tem acesso total aos nossos cursos.</p>
      <div class="w-full max-w-md bg-white/50 dark:bg-white/5 p-4 rounded-xl border border-slate-200 dark:border-slate-800 mb-8">
        <div class="flex justify-between gap-x-6 py-3 border-b border-slate-200 dark:border-slate-800">
          <p class="text-slate-500 dark:text-slate-400 text-sm font-normal leading-normal">Plano</p>
          <p class="text-slate-900 dark:text-white text-sm font-medium leading-normal text-right">Plano Premium Anual</p>
        </div>
        <div class="flex justify-between gap-x-6 py-3 border-b border-slate-200 dark:border-slate-800">
          <p class="text-slate-500 dark:text-slate-400 text-sm font-normal leading-normal">Valor</p>
          <p class="text-slate-900 dark:text-white text-sm font-medium leading-normal text-right">R$ 199,90</p>
        </div>
        <div class="flex justify-between gap-x-6 py-3 border-b border-slate-200 dark:border-slate-800">
          <p class="text-slate-500 dark:text-slate-400 text-sm font-normal leading-normal">Data</p>
          <p class="text-slate-900 dark:text-white text-sm font-medium leading-normal text-right">25 de Outubro de 2023, 14:35</p>
        </div>
        <div class="flex justify-between gap-x-6 py-3">
          <p class="text-slate-500 dark:text-slate-400 text-sm font-normal leading-normal">Método</p>
          <p class="text-slate-900 dark:text-white text-sm font-medium leading-normal text-right">PIX</p>
        </div>
      </div>
      <div class="w-full max-w-md">
        <button class="flex min-w-[84px] w-full max-w-[480px] mx-auto cursor-pointer items-center justify-center overflow-hidden rounded-xl h-12 px-5 flex-1 bg-primary text-white text-base font-bold leading-normal tracking-[0.015em]">
          <span class="truncate">Começar a aprender</span>
        </button>
      </div>
    </div>
  </div>
</body>
</html>
</body>
</html>
