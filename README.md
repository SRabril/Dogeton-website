# Dogeton-website
Dogeton el meme revolucionario en TON
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="DOGETON - El perro oficial de TON Blockchain. ¡Such blockchain, very fast, wow!">
    <meta name="keywords" content="DOGETON, TON, meme coin, crypto, shiba, doge, blockchain">
    <meta property="og:title" content="DOGETON - Much TON, Very Moon!">
    <meta property="og:description" content="Primera meme coin nativa en TON Blockchain">
    <meta property="og:image" content="https://dogeton.xyz/assets/og-image.png">
    <meta name="twitter:card" content="summary_large_image">
    
    <title>DOGETON 🐕 - Official Meme Coin of TON</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/x-icon" href="assets/favicon.ico">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@700&family=Montserrat:wght@400;600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <a href="#" class="logo">
                <span class="doge-icon">🐕</span>
                <span class="logo-text">DOGETON</span>
                <span class="ton-badge">TON</span>
            </a>
            <div class="nav-links">
                <a href="#home">Inicio</a>
                <a href="#about">Acerca</a>
                <a href="#tokenomics">Tokenomics</a>
                <a href="#roadmap">Roadmap</a>
                <a href="#buy">Cómo Comprar</a>
                <a href="#community">Comunidad</a>
            </div>
            <button class="connect-wallet" id="connectWallet">
                <i class="fas fa-wallet"></i> Conectar Wallet
            </button>
            <button class="menu-toggle" id="menuToggle">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1 class="hero-title">
                    <span class="wow">MUCH</span>
                    <span class="ton-highlight">TON</span>
                    <span class="wow">VERY</span>
                    <span class="moon">MOON</span>
                    <span class="wow">WOW</span>
                </h1>
                <p class="hero-subtitle">El primer perro nativo en TON Blockchain. ¡Únete a la Shiba Army!</p>
                
                <div class="hero-stats">
                    <div class="stat">
                        <div class="stat-value" id="marketCap">$0.00</div>
                        <div class="stat-label">Market Cap</div>
                    </div>
                    <div class="stat">
                        <div class="stat-value" id="holders">1,234</div>
                        <div class="stat-label">Holders</div>
                    </div>
                    <div class="stat">
                        <div class="stat-value" id="price">$0.0000</div>
                        <div class="stat-label">Precio</div>
                    </div>
                </div>

                <div class="hero-buttons">
                    <a href="#buy" class="btn btn-primary">
                        <i class="fas fa-rocket"></i> Comprar $DOGE
                    </a>
                    <a href="https://github.com/tondogecoin/dogeton" target="_blank" class="btn btn-secondary">
                        <i class="fab fa-github"></i> Ver Contrato
                    </a>
                    <a href="https://t.me/dogeton_official" target="_blank" class="btn btn-telegram">
                        <i class="fab fa-telegram"></i> Telegram
                    </a>
                </div>

                <div class="contract-address">
                    <div class="contract-label">Contrato:</div>
                    <div class="address-box" id="contractAddress">
                        EQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
                    </div>
                    <button class="copy-btn" id="copyAddress">
                        <i class="far fa-copy"></i>
                    </button>
                </div>
            </div>
            <div class="hero-image">
                <div class="doge-meme">
                    <img src="https://i.imgur.com/3Q1Yc7v.png" alt="DOGETON Meme" class="meme-img">
                    <div class="speech-bubble">¡Such Fast!<br>¡Very Cheap!<br>¡Wow!</div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <div class="container">
            <h2 class="section-title">¿Qué es DOGETON? 🐕</h2>
            <div class="about-content">
                <div class="about-text">
                    <p><strong>DOGETON</strong> es la primera meme coin nativa construida sobre <strong>The Open Network (TON)</strong>, combinando el espíritu divertido de Doge con la tecnología revolucionaria de TON.</p>
                    
                    <div class="features">
                        <div class="feature">
                            <div class="feature-icon">⚡</div>
                            <h3>Super Rápido</h3>
                            <p>Transacciones en segundos con fees mínimos</p>
                        </div>
                        <div class="feature">
                            <div class="feature-icon">🔒</div>
                            <h3>100% Seguro</h3>
                            <p>Contrato verificado y liquidez bloqueada</p>
                        </div>
                        <div class="feature">
                            <div class="feature-icon">🌐</div>
                            <h3>Integración TON</h3>
                            <p>Compatible con toda la ecosystema TON</p>
                        </div>
                        <div class="feature">
                            <div class="feature-icon">🎮</div>
                            <h3>Utilidad Real</h3>
                            <p>NFTs, staking, y juegos P2E próximamente</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tokenomics -->
    <section class="section tokenomics" id="tokenomics">
        <div class="container">
            <h2 class="section-title">Tokenomics 📊</h2>
            <div class="tokenomics-grid">
                <div class="chart-container">
                    <div class="pie-chart" id="tokenPieChart">
                        <!-- Pie chart will be generated with JS -->
                    </div>
                </div>
                <div class="tokenomics-details">
                    <div class="token-info">
                        <h3>Información del Token</h3>
                        <table>
                            <tr>
                                <td>Nombre:</td>
                                <td><strong>DOGETON</strong></td>
                            </tr>
                            <tr>
                                <td>Símbolo:</td>
                                <td><strong>$DOGE</strong></td>
                            </tr>
                            <tr>
                                <td>Blockchain:</td>
                                <td><strong>TON (The Open Network)</strong></td>
                            </tr>
                            <tr>
                                <td>Suministro Total:</td>
                                <td><strong>1,000,000,000</strong></td>
                            </tr>
                            <tr>
                                <td>Decimales:</td>
                                <td><strong>9</strong></td>
                            </tr>
                            <tr>
                                <td>Tax:</td>
                                <td><strong>0%</strong> (¡Cero!)</td>
                            </tr>
                        </table>
                    </div>
                    
                    <div class="distribution">
                        <h3>Distribución</h3>
                        <ul>
                            <li><span class="dist-color" style="background:#FF6B6B"></span> 40% Fair Launch</li>
                            <li><span class="dist-color" style="background:#4ECDC4"></span> 30% Liquidez</li>
                            <li><span class="dist-color" style="background:#FFD166"></span> 20% Marketing</li>
                            <li><span class="dist-color" style="background:#06D6A0"></span> 10% Equipo</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Roadmap -->
    <section class="section roadmap" id="roadmap">
        <div class="container">
            <h2 class="section-title">Roadmap 🗺️</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-date">Q1 2024</div>
                    <div class="timeline-content">
                        <h3>🚀 Lanzamiento</h3>
                        <p>• Contrato verificado en TON</p>
                        <p>• Fair Launch en STON.fi</p>
                        <p>• Sitio web y redes sociales</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-date">Q2 2024</div>
                    <div class="timeline-content">
                        <h3>📈 Expansión</h3>
                        <p>• Listado en 3 CEXs de TON</p>
                        <p>• 10,000 holders objetivo</p>
                        <p>• Campaña de marketing viral</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-date">Q3 2024</div>
                    <div class="timeline-content">
                        <h3>🎮 Ecosistema</h3>
                        <p>• NFTs "Shiba Army"</p>
                        <p>• Juego P2E "Doge Race"</p>
                        <p>• Staking platform</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-date">Q4 2024</div>
                    <div class="timeline-content">
                        <h3>🌙 Al Espacio</h3>
                        <p>• Bridge multi-cadena</p>
                        <p>• DOGETON DeFi platform</p>
                        <p>• Partnerships estratégicos</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How to Buy -->
    <section class="section buy" id="buy">
        <div class="container">
            <h2 class="section-title">Cómo Comprar DOGETON 📈</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Obtén TON</h3>
                    <p>Compra Toncoin en cualquier exchange y envíalo a tu wallet de TON (Tonkeeper, Tonhub)</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Conéctate a DEX</h3>
                    <p>Ve a <a href="https://ston.fi" target="_blank">STON.fi</a> o <a href="https://dedust.io" target="_blank">DeDust.io</a> y conecta tu wallet</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Swap por DOGETON</h3>
                    <p>Busca el par TON/DOGE y haz swap</p>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>¡HODL!</h3>
                    <p>Guarda tus tokens y únete a la comunidad para updates</p>
                </div>
            </div>
            
            <div class="dex-buttons">
                <a href="https://ston.fi" target="_blank" class="dex-btn ston">
                    <img src="https://ston.fi/favicon.ico" alt="STON.fi"> Comprar en STON.fi
                </a>
                <a href="https://dedust.io" target="_blank" class="dex-btn dedust">
                    <img src="https://dedust.io/favicon.ico" alt="DeDust"> Comprar en DeDust
                </a>
            </div>
        </div>
    </section>

    <!-- Community -->
    <section class="section community" id="community">
        <div class="container">
            <h2 class="section-title">Únete a la Comunidad 🐕‍🦺</h2>
            <p class="section-subtitle">La Shiba Army está creciendo. ¡Sé parte de la manada!</p>
            
            <div class="social-links">
                <a href="https://t.me/dogeton_official" target="_blank" class="social-btn telegram">
                    <i class="fab fa-telegram"></i> Telegram
                </a>
                <a href="https://twitter.com/dogeton_ton" target="_blank" class="social-btn twitter">
                    <i class="fab fa-twitter"></i> Twitter
                </a>
                <a href="https://github.com/dogeton" target="_blank" class="social-btn github">
                    <i class="fab fa-github"></i> GitHub
                </a>
                <a href="https://discord.gg/dogeton" target="_blank" class="social-btn discord">
                    <i class="fab fa-discord"></i> Discord
                </a>
            </div>
            
            <div class="meme-gallery">
                <h3>Meme Gallery 🎭</h3>
                <div class="gallery">
                    <img src="https://i.imgur.com/1.jpg" alt="DOGETON Meme 1" class="meme">
                    <img src="https://i.imgur.com/2.jpg" alt="DOGETON Meme 2" class="meme">
                    <img src="https://i.imgur.com/3.jpg" alt="DOGETON Meme 3" class="meme">
                    <img src="https://i.imgur.com/4.jpg" alt="DOGETON Meme 4" class="meme">
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">
                    <span class="doge-icon">🐕</span>
                    <span class="logo-text">DOGETON</span>
                </div>
                <p class="footer-disclaimer">
                    <strong>ADVERTENCIA:</strong> DOGETON es un token meme con fines de entretenimiento. 
                    No es una inversión financiera. Las criptomonedas son de alto riesgo. 
                    Nunca inviertas más de lo que estés dispuesto a perder. 
                    DYOR (Do Your Own Research).
                </p>
                <div class="footer-links">
                    <a href="#privacy">Política de Privacidad</a> | 
                    <a href="#terms">Términos de Uso</a> | 
                    <a href="#contact">Contacto</a>
                </div>
                <p class="copyright">© 2024 DOGETON. Todos los derechos reservados. Such rights, very legal, wow.</p>
            </div>
        </div>
    </footer>

    <!-- Ticker -->
    <div class="ticker">
        <div class="ticker-content">
            <span>🚀 DOGETON A LA LUNA 🚀</span>
            <span>🐕 SUCH TON VERY WOW 🐕</span>
            <span>💎 1B = 1B 💎</span>
            <span>🌙 HODL TO THE MOON 🌙</span>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
{
  "name": "DOGETON - Official Meme Coin",
  "short_name": "DOGETON",
  "description": "El primer perro nativo en TON Blockchain",
  "start_url": "/",
  "display": "standalone",
  "background_color": "#1A1A2E",
  "theme_color": "#FFD700",
  "icons": [
    {
      "src": "assets/icon-192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "assets/icon-512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
User-agent: *
Allow: /
Sitemap: https://dogeton.xyz/sitemap.xml
