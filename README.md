<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>P2P Money Exchange | Trusted PayPal to Bank Transfers</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2980b9;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
        }
        
        .navbar {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .hero-section {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 80px 0;
        }
        
        .exchange-card {
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            margin-bottom: 20px;
        }
        
        .exchange-card:hover {
            transform: translateY(-5px);
        }
        
        .badge-trusted {
            background-color: #2ecc71;
        }
        
        .how-it-works-step {
            text-align: center;
            padding: 20px;
        }
        
        .step-icon {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 40px 0;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-light sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#" style="color: var(--primary-color);">
                <i class="fas fa-exchange-alt me-2"></i>P2PExchange
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#how-it-works">How It Works</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#exchange-ads">Exchange Ads</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#rates">Rates</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#faq">FAQ</a>
                    </li>
                    <li class="nav-item ms-lg-3">
                        <a class="btn btn-outline-primary" href="#">Login</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary" href="#">Register</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section bg-primary text-white">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <h1 class="display-4 fw-bold mb-4">Exchange PayPal to Bank Transfer Peer-to-Peer</h1>
                    <p class="lead mb-4">Trade directly with other users at better rates than traditional exchanges. Fast, secure, and trusted by thousands.</p>
                    <div class="d-flex gap-3">
                        <a href="#" class="btn btn-light btn-lg px-4">Start Trading</a>
                        <a href="#how-it-works" class="btn btn-outline-light btn-lg px-4">Learn More</a>
                    </div>
                </div>
                <div class="col-lg-6 d-none d-lg-block">
                    <img src="https://via.placeholder.com/600x400" alt="Exchange Illustration" class="img-fluid rounded">
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Bar -->
    <section class="py-4 bg-light">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-3">
                    <h3 class="fw-bold">10,000+</h3>
                    <p class="text-muted">Successful Trades</p>
                </div>
                <div class="col-md-3">
                    <h3 class="fw-bold">2,500+</h3>
                    <p class="text-muted">Verified Users</p>
                </div>
                <div class="col-md-3">
                    <h3 class="fw-bold">0.5%</h3>
                    <p class="text-muted">Lowest Fees</p>
                </div>
                <div class="col-md-3">
                    <h3 class="fw-bold">24/7</h3>
                    <p class="text-muted">Support</p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold">How It Works</h2>
                <p class="text-muted lead">Exchange money in just 3 simple steps</p>
            </div>
            
            <div class="row">
                <div class="col-md-4 how-it-works-step">
                    <div class="step-icon">
                        <i class="fas fa-user-plus"></i>
                    </div>
                    <h4>1. Create Account</h4>
                    <p>Register and complete your profile verification to start trading.</p>
                </div>
                <div class="col-md-4 how-it-works-step">
                    <div class="step-icon">
                        <i class="fas fa-ad"></i>
                    </div>
                    <h4>2. Post/Create Ad</h4>
                    <p>Create an exchange offer or browse existing ads from other users.</p>
                </div>
                <div class="col-md-4 how-it-works-step">
                    <div class="step-icon">
                        <i class="fas fa-exchange-alt"></i>
                    </div>
                    <h4>3. Exchange Securely</h4>
                    <p>Our escrow system protects both parties until the trade is complete.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Exchange Ads Section -->
    <section id="exchange-ads" class="py-5 bg-light">
        <div class="container">
            <div class="d-flex justify-content-between align-items-center mb-4">
                <h2 class="fw-bold">Available Exchange Offers</h2>
                <a href="#" class="btn btn-outline-primary">Post Your Ad</a>
            </div>
            
            <div class="row">
                <!-- Sample Exchange Ad 1 -->
                <div class="col-md-6 col-lg-4">
                    <div class="exchange-card p-4 bg-white">
                        <div class="d-flex justify-content-between mb-3">
                            <div>
                                <span class="badge bg-success me-2">Verified</span>
                                <span class="badge bg-primary">High Limit</span>
                            </div>
                            <div class="text-muted">5 min ago</div>
                        </div>
                        
                        <div class="d-flex align-items-center mb-3">
                            <div class="bg-light rounded-circle p-3 me-3">
                                <i class="fab fa-paypal fa-2x text-primary"></i>
                            </div>
                            <div>
                                <h5 class="mb-0">PayPal USD</h5>
                                <small class="text-muted">Personal/Business</small>
                            </div>
                        </div>
                        
                        <div class="d-flex align-items-center mb-3">
                            <div class="bg-light rounded-circle p-3 me-3">
                                <i class="fas fa-university fa-2x text-success"></i>
                            </div>
                            <div>
                                <h5 class="mb-0">Bank Transfer</h5>
                                <small class="text-muted">Any Bangladesh Bank</small>
                            </div>
                        </div>
                        
                        <div class="row mb-3">
                            <div class="col-6">
                                <small class="text-muted">Available</small>
                                <h5 class="mb-0">$250.00</h5>
                            </div>
                            <div class="col-6">
                                <small class="text-muted">Exchange Rate</small>
                                <h5 class="mb-0">1 USD = 105 BDT</h5>
                            </div>
                        </div>
                        
                        <div class="d-flex justify-content-between">
                            <div>
                                <small class="text-muted">Trader</small>
                                <h5 class="mb-0">JohnDoe</h5>
                            </div>
                            <a href="#" class="btn btn-primary align-self-center">Exchange Now</a>
                        </div>
                    </div>
                </div>
                
                <!-- Sample Exchange Ad 2 -->
                <div class="col-md-6 col-lg-4">
                    <div class="exchange-card p-4 bg-white">
                        <div class="d-flex justify-content-between mb-3">
                            <div>
                                <span class="badge bg-success me-2">Verified</span>
                            <span class="badge bg-warning">Medium Limit</span>
                            </div>
                            <div class="text-muted">15 min ago</div>
                        </div>
                        
                        <div class="d-flex align-items-center mb-3">
                            <div class="bg-light rounded-circle p-3 me-3">
                                <i class="fab fa-paypal fa-2x text-primary"></i>
                            </div>
                            <div>
                                <h5 class="mb-0">PayPal EUR</h5>
                                <small class="text-muted">Personal Only</small>
                            </div>
                        </div>
                        
                        <div class="d-flex align-items-center mb-3">
                            <div class="bg-light rounded-circle p-3 me-3">
                                <i class="fas fa-mobile-alt fa-2x text-info"></i>
                            </div>
                            <div>
                                <h5 class="mb-0">Mobile Money</h5>
                                <small class="text-muted">bKash/Nagad</small>
                            </div>
                        </div>
                        
                        <div class="row mb-3">
                            <div class="col-6">
                                <small class="text-muted">Available</small>
                                <h5 class="mb-0">€150.00</h5>
                            </div>
                            <div class="col-6">
                                <small class="text-muted">Exchange Rate</small>
                                <h5 class="mb-0">1 EUR = 115 BDT</h5>
                            </div>
                        </div>
                        
                        <div class="d-flex justify-content-between">
                            <div>
                                <small class="text-muted">Trader</small>
                                <h5 class="mb-0">SarahSmith</h5>
                            </div>
                            <a href="#" class="btn btn-primary align-self-center">Exchange Now</a>
                        </div>
                    </div>
                </div>
                
                <!-- Sample Exchange Ad 3 -->
                <div class="col-md-6 col-lg-4">
                    <div class="exchange-card p-4 bg-white">
                        <div class="d-flex justify-content-between mb-3">
                            <div>
                                <span class="badge bg-success me-2">Verified</span>
                                <span class="badge bg-danger">Low Limit</span>
                            </div>
                            <div class="text-muted">1 hour ago</div>
                        </div>
                        
                        <div class="d-flex align-items-center mb-3">
                            <div class="bg-light rounded-circle p-3 me-3">
                                <i class="fas fa-university fa-2x text-success"></i>
                            </div>
                            <div>
                                <h5 class="mb-0">Bank Transfer</h5>
                                <small class="text-muted">US Bank Account</small>
                            </div>
                        </div>
                        
                        <div class="d-flex align-items-center mb-3">
                            <div class="bg-light rounded-circle p-3 me-3">
                                <i class="fab fa-paypal fa-2x text-primary"></i>
                            </div>
                            <div>
                                <h5 class="mb-0">PayPal USD</h5>
                                <small class="text-muted">Business Only</small>
                            </div>
                        </div>
                        
                        <div class="row mb-3">
                            <div class="col-6">
                                <small class="text-muted">Available</small>
                                <h5 class="mb-0">$500.00</h5>
                            </div>
                            <div class="col-6">
                                <small class="text-muted">Exchange Rate</small>
                                <h5 class="mb-0">1 USD = 103 BDT</h5>
                            </div>
                        </div>
                        
                        <div class="d-flex justify-content-between">
                            <div>
                                <small class="text-muted">Trader</small>
                                <h5 class="mb-0">MikeJohnson</h5>
                            </div>
                            <a href="#" class="btn btn-primary align-self-center">Exchange Now</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-4">
                <a href="#" class="btn btn-outline-primary">View All Exchange Offers</a>
            </div>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold">Why Choose Our Platform</h2>
                <p class="text-muted lead">The safest way to exchange money peer-to-peer</p>
            </div>
            
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="p-4 text-center">
                        <div class="bg-primary bg-opacity-10 rounded-circle d-inline-flex p-4 mb-3">
                            <i class="fas fa-shield-alt fa-2x text-primary"></i>
                        </div>
                        <h4>Secure Escrow</h4>
                        <p class="text-muted">Funds are held in escrow until both parties confirm the transaction is complete.</p>
                    </div>
                </div>
                
                <div class="col-md-4 mb-4">
                    <div class="p-4 text-center">
                        <div class="bg-primary bg-opacity-10 rounded-circle d-inline-flex p-4 mb-3">
                            <i class="fas fa-user-check fa-2x text-primary"></i>
                        </div>
                        <h4>Verified Users</h4>
                        <p class="text-muted">All users undergo identity verification to ensure a trusted community.</p>
                    </div>
                </div>
                
                <div class="col-md-4 mb-4">
                    <div class="p-4 text-center">
                        <div class="bg-primary bg-opacity-10 rounded-circle d-inline-flex p-4 mb-3">
                            <i class="fas fa-headset fa-2x text-primary"></i>
                        </div>
                        <h4>24/7 Support</h4>
                        <p class="text-muted">Our support team is always available to help resolve any issues.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold">Frequently Asked Questions</h2>
            </div>
            
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="accordion" id="faqAccordion">
                        <!-- FAQ Item 1 -->
                        <div class="accordion-item mb-3 border-0 shadow-sm">
                            <h3 class="accordion-header" id="headingOne">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
                                    How does the escrow system work?
                                </button>
                            </h3>
                            <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#faqAccordion">
                                <div class="accordion-body">
                                    Our escrow system holds the sender's funds securely until the receiver confirms they've sent the agreed amount. Once both parties confirm, the funds are released.
                                </div>
                            </div>
                        </div>
                        
                        <!-- FAQ Item 2 -->
                        <div class="accordion-item mb-3 border-0 shadow-sm">
                            <h3 class="accordion-header" id="headingTwo">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo">
                                    What verification is required?
                                </button>
                            </h3>
                            <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
                                <div class="accordion-body">
                                    We require government-issued ID, proof of address, and in some cases a selfie with your ID to verify your identity and prevent fraud.
                                </div>
                            </div>
                        </div>
                        
                        <!-- FAQ Item 3 -->
                        <div>