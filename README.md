<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invest Expert | Seu Futuro Financeiro Começa Aqui</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #1e3a8a 0%, #2563eb 50%, #3b82f6 100%);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .cta-pulse {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% {
                box-shadow: 0 0 0 0 rgba(59, 130, 246, 0.7);
            }
            70% {
                box-shadow: 0 0 0 10px rgba(59, 130, 246, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(59, 130, 246, 0);
            }
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800">
    <!-- Header -->
    <header class="hero-gradient text-white">
        <div class="container mx-auto px-6 py-12 md:py-20">
            <div class="flex justify-between items-center mb-12">
                <div class="text-2xl font-bold">Invest<span class="text-blue-200">Expert</span></div>
                <a href="#cta" class="bg-white text-blue-600 px-6 py-2 rounded-full font-medium hover:bg-blue-50 transition duration-300">Comece Agora</a>
            </div>
            
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-6">Domine o mercado financeiro com estratégias de especialistas</h1>
                    <p class="text-xl text-blue-100 mb-8">Aprenda com os melhores investidores do mercado e alcance resultados extraordinários com nossa metodologia exclusiva.</p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="https://shre.ink/acesseja0" class="bg-yellow-400 hover:bg-yellow-300 text-blue-900 font-bold px-8 py-4 rounded-lg text-center transition duration-300 cta-pulse">
                            QUERO COMEÇAR AGORA <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                        <a href="#features" class="border-2 border-white text-white hover:bg-white hover:text-blue-600 font-medium px-8 py-4 rounded-lg text-center transition duration-300">
                            <i class="fas fa-play-circle mr-2"></i> Ver Vídeo
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="https://images.unsplash.com/photo-1554224155-6726b3ff858f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80" alt="Investimentos" class="rounded-xl shadow-2xl max-w-md w-full">
                </div>
            </div>
        </div>
    </header>

    <!-- Trust Badges -->
    <section class="bg-gray-50 py-8">
        <div class="container mx-auto px-6">
            <p class="text-center text-gray-500 mb-6">Confiamos em mais de 50.000 investidores</p>
            <div class="flex flex-wrap justify-center items-center gap-8 md:gap-16">
                <img src="https://logo.clearbit.com/forbes.com" alt="Forbes" class="h-8 opacity-70">
                <img src="https://logo.clearbit.com/bloomberg.com" alt="Bloomberg" class="h-8 opacity-70">
                <img src="https://logo.clearbit.com/economist.com" alt="The Economist" class="h-8 opacity-70">
                <img src="https://logo.clearbit.com/financialtimes.com" alt="Financial Times" class="h-8 opacity-70">
            </div>
        </div>
    </section>

    <!-- Features -->
    <section id="features" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Método Invest Expert</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">A estratégia comprovada que transformou milhares de investidores</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-chart-line text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Análise Especializada</h3>
                    <p class="text-gray-600">Acesso às mesmas técnicas de análise usadas por gestores de fundos bilionários para identificar oportunidades.</p>
                </div>
                
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="w-14 h-14 bg-green-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-university text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Gestão de Risco</h3>
                    <p class="text-gray-600">Sistema de proteção de capital desenvolvido por nossos especialistas com décadas de experiência.</p>
                </div>
                
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="w-14 h-14 bg-purple-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-hand-holding-usd text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Mentoria Personalizada</h3>
                    <p class="text-gray-600">Acompanhamento direto com nossos experts para adaptar as estratégias ao seu perfil.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Results -->
    <section class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80" alt="Resultados" class="rounded-xl shadow-lg w-full max-w-md">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">Resultados Comprovados</h2>
                    <div class="mb-8">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <p class="font-medium">+92% dos alunos superam o CDI em 12 meses</p>
                        </div>
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <p class="font-medium">+7.500 alunos alcançaram a independência financeira</p>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <p class="font-medium">Retorno médio de 3.8% ao mês após o treinamento</p>
                        </div>
                    </div>
                    <a href="https://shre.ink/acesseja0" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold px-8 py-4 rounded-lg transition duration-300">
                        QUERO ESSES RESULTADOS <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">O que dizem nossos investidores</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Depoimentos reais de quem transformou seus investimentos</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/43.jpg" alt="Cliente" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Ana Carolina</h4>
                            <p class="text-blue-600 text-sm">Engenheira</p>
                        </div>
                    </div>
                    <p class="text-gray-600">"O Invest Expert mudou completamente minha visão sobre investimentos. Em 1 ano meu patrimônio cresceu 280%!"</p>
                    <div class="flex mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Cliente" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Ricardo Almeida</h4>
                            <p class="text-blue-600 text-sm">Médico</p>
                        </div>
                    </div>
                    <p class="text-gray-600">"Finalmente entendi como os grandes investidores pensam. As estratégias do Invest Expert são revolucionárias."</p>
                    <div class="flex mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Cliente" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Fernanda Gomes</h4>
                            <p class="text-blue-600 text-sm">Empresária</p>
                        </div>
                    </div>
                    <p class="text-gray-600">"A mentoria personalizada fez toda diferença. Em 4 meses já tinha resultados melhores que em 5 anos investindo por conta."</p>
                    <div class="flex mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing -->
    <section class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Invista no seu futuro</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Escolha o plano ideal para sua jornada como investidor expert</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
                <div class="bg-white p-8 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-xl font-bold mb-2">Essencial</h3>
                    <p class="text-gray-600 mb-6">Para quem está começando</p>
                    <div class="mb-6">
                        <span class="text-4xl font-bold">R$ 597</span>
                        <span class="text-gray-500">/ à vista</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Acesso ao curso completo</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>5 estratégias de investimento</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Suporte por e-mail</span>
                        </li>
                    </ul>
                    <a href="https://shre.ink/acesseja0" class="block bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium text-center py-3 rounded-lg transition duration-300">Começar Agora</a>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-2xl border-2 border-blue-500 transform scale-105">
                    <div class="bg-blue-500 text-white text-xs font-bold px-3 py-1 rounded-full inline-block mb-4">MAIS POPULAR</div>
                    <h3 class="text-xl font-bold mb-2">Expert</h3>
                    <p class="text-gray-600 mb-6">O mais escolhido por investidores</p>
                    <div class="mb-6">
                        <span class="text-4xl font-bold">R$ 1.297</span>
                        <span class="text-gray-500">/ à vista</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Tudo do plano Essencial</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>+12 estratégias avançadas</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Suporte prioritário</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Análises semanais de mercado</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Comunidade exclusiva</span>
                        </li>
                    </ul>
                    <a href="https://shre.ink/acesseja0" class="block bg-blue-600 hover:bg-blue-700 text-white font-bold text-center py-3 rounded-lg transition duration-300">Quero o Expert</a>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-xl font-bold mb-2">Master</h3>
                    <p class="text-gray-600 mb-6">Para quem quer resultados extraordinários</p>
                    <div class="mb-6">
                        <span class="text-4xl font-bold">R$ 2.997</span>
                        <span class="text-gray-500">/ à vista</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Tudo do plano Expert</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Mentoria individual mensal</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Análise personalizada de portfólio</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-2"></i>
                            <span>Acesso a oportunidades exclusivas</span>
                        </li>
                    </ul>
                    <a href="https://shre.ink/acesseja0" class="block bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium text-center py-3 rounded-lg transition duration-300">Quero o Master</a>
                </div>
            </div>
            
            <div class="text-center mt-12 text-gray-600">
                <p>Pagamento seguro via cartão de crédito, boleto ou PIX</p>
                <div class="flex justify-center mt-4 gap-6">
                    <i class="fab fa-cc-visa text-3xl text-gray-500"></i>
                    <i class="fab fa-cc-mastercard text-3xl text-gray-500"></i>
                    <i class="fab fa-cc-amex text-3xl text-gray-500"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6 max-w-4xl">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Perguntas Frequentes</h2>
                <p class="text-xl text-gray-600">Tire suas dúvidas sobre o Invest Expert</p>
            </div>
            
            <div class="space-y-4">
                <div class="border border-gray-200 rounded-lg overflow-hidden">
                    <button class="faq-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition duration-300 flex justify-between items-center">
                        <span class="font-medium text-lg">Quem são os especialistas do Invest Expert?</span>
                        <i class="fas fa-plus text-blue-600"></i>
                    </button>
                    <div class="faq-content hidden p-6 border-t border-gray-200">
                        <p class="text-gray-600">Nossa equipe é composta por gestores de fundos multimercado, analistas certificados e investidores com décadas de experiência no mercado financeiro. Todos passam por um rigoroso processo de seleção para garantir a qualidade do conteúdo.</p>
                    </div>
                </div>
                
                <div class="border border-gray-200 rounded-lg overflow-hidden">
                    <button class="faq-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition duration-300 flex justify-between items-center">
                        <span class="font-medium text-lg">Quanto tempo leva para ver resultados?</span>
                        <i class="fas fa-plus text-blue-600"></i>
                    </button>
                    <div class="faq-content hidden p-6 border-t border-gray-200">
                        <p class="text-gray-600">A maioria de nossos alunos começa a implementar as estratégias com sucesso em 2-3 meses. Resultados financeiros significativos geralmente aparecem entre 6-12 meses, dependendo do capital inicial e da dedicação do aluno.</p>
                    </div>
                </div>
                
                <div class="border border-gray-200 rounded-lg overflow-hidden">
                    <button class="faq-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition duration-300 flex justify-between items-center">
                        <span class="font-medium text-lg">Preciso de muito dinheiro para começar?</span>
                        <i class="fas fa-plus text-blue-600"></i>
                    </button>
                    <div class="faq-content hidden p-6 border-t border-gray-200">
                        <p class="text-gray-600">Não. Ensinamos estratégias adaptáveis a diferentes tamanhos de capital. Muitos alunos começam com R$ 1.000-5.000 e vão aumentando seus investimentos conforme ganham confiança e experiência.</p>
                    </div>
                </div>
                
                <div class="border border-gray-200 rounded-lg overflow-hidden">
                    <button class="faq-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition duration-300 flex justify-between items-center">
                        <span class="font-medium text-lg">Há garantia de resultados?</span>
                        <i class="fas fa-plus text-blue-600"></i>
                    </button>
                    <div class="faq-content hidden p-6 border-t border-gray-200">
                        <p class="text-gray-600">Oferecemos garantia incondicional de 15 dias: se você não estiver satisfeito, devolvemos 100% do seu investimento. Quanto aos resultados financeiros, eles dependem da aplicação correta das estratégias e das condições de mercado.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA -->
    <section id="cta" class="py-20 hero-gradient text-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Pronto para se tornar um Invest Expert?</h2>
            <p class="text-xl text-blue-100 mb-8 max-w-2xl mx-auto">Transforme sua maneira de investir com as estratégias dos maiores especialistas do mercado.</p>
            
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="https://shre.ink/acesseja0" class="bg-yellow-400 hover:bg-yellow-300 text-blue-900 font-bold px-8 py-4 rounded-lg transition duration-300 text-lg">
                    QUERO COMEÇAR AGORA <i class="fas fa-arrow-right ml-2"></i>
                </a>
                <a href="#pricing" class="border-2 border-white hover:bg-white hover:text-blue-600 font-medium px-8 py-4 rounded-lg transition duration-300 text-lg">
                    VER PLANOS <i class="fas fa-wallet ml-2"></i>
                </a>
            </div>
            
            <div class="mt-12 bg-white bg-opacity-10 rounded-xl p-6 max-w-2xl mx-auto">
                <div class="flex items-center justify-center">
                    <img src="https://randomuser.me/api/portraits/men/75.jpg" alt="Especialista" class="w-16 h-16 rounded-full border-2 border-white mr-4">
                    <div class="text-left">
                        <p class="font-bold">Ricardo Silva</p>
                        <p class="text-blue-200 text-sm">Fundador do Invest Expert</p>
                    </div>
                </div>
                <p class="mt-4 italic">"Por mais de 15 anos no mercado financeiro, desenvolvi um método que qualquer pessoa pode aplicar para obter resultados extraordinários. Agora quero compartilhar esse conhecimento com você."</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Invest Expert</h3>
                    <p class="text-gray-400">Transformando investidores comuns em especialistas do mercado desde 2010.</p>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">Links Rápidos</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Sobre Nós</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Depoimentos</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Termos de Uso</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Política de Privacidade</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">Contato</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-2"></i>
                            <span>contato@investexpert.com</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone mr-2"></i>
                            <span>(11) 98765-4321</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-map-marker-alt mr-2"></i>
                            <span>São Paulo - SP</span>
                        </li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">Redes Sociais</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition duration-300">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-400 transition duration-300">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-pink-600 transition duration-300">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-red-600 transition duration-300">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
                <p>© 2023 Invest Expert. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>

    <script>
        // FAQ toggle
        document.querySelectorAll('.faq-toggle').forEach(button => {
            button.addEventListener('click', () => {
                const content = button.nextElementSibling;
                const icon = button.querySelector('i');
                
                if (content.classList.contains('hidden')) {
                    content.classList.remove('hidden');
                    icon.classList.remove('fa-plus');
                    icon.classList.add('fa-minus');
                } else {
                    content.classList.add('hidden');
                    icon.classList.remove('fa-minus');
                    icon.classList.add('fa-plus');
                }
            });
        });

        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                if (this.getAttribute('href') === '#') return;
                
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
