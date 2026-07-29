<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>番茄商城 - 你的专属购物平台</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <style>
        :root { --primary: #ff6b6b; --secondary: #ffa07a; --dark: #2c3e50; --light: #ecf0f1; --success: #27ae60; --warning: #f39c12; }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Noto Sans SC', sans-serif; }
        body { background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); color: var(--dark); min-height: 100vh; }
        /* 导航栏 */
        nav { position: fixed; top: 0; width: 100%; background: rgba(255,255,255,0.95); backdrop-filter: blur(10px); z-index: 1000; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        .nav-container { display: flex; justify-content: space-between; align-items: center; max-width: 1200px; margin: 0 auto; padding: 15px 20px; }
        .logo { font-size: 1.8rem; font-weight: 900; background: linear-gradient(135deg, var(--primary), var(--secondary)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; letter-spacing: 1px; }
        .nav-links { display: flex; gap: 30px; list-style: none; }
        .nav-links a { color: var(--dark); text-decoration: none; font-weight: 500; transition: color 0.3s; cursor: pointer; }
        .nav-links a:hover, .nav-links a.active { color: var(--primary); }
        .cart-icon { position: relative; font-size: 1.5rem; cursor: pointer; }
        .cart-count { position: absolute; top: -8px; right: -8px; background: var(--primary); color: white; border-radius: 50%; width: 20px; height: 20px; display: flex; align-items: center; justify-content: center; font-size: 0.8rem; font-weight: bold; }
        .site-like-section { display: flex; align-items: center; gap: 8px; cursor: pointer; transition: color 0.3s; }
        .site-like-button { background: none; border: none; font-size: 1.5rem; cursor: pointer; transition: transform 0.3s; }
        .site-like-button:hover { transform: scale(1.2); }
        .site-like-button.liked { color: var(--primary); }
        .site-like-count { font-weight: 600; }
        /* 主要内容区 */
        .main-content { margin-top: 80px; padding-bottom: 40px; }
        .hero { text-align: center; padding: 60px 20px; background: linear-gradient(135deg, var(--primary), var(--secondary)); color: white; border-radius: 0 0 20px 20px; margin-bottom: 40px; }
        .hero h1 { font-size: 3rem; margin-bottom: 15px; }
        .hero p { font-size: 1.2rem; opacity: 0.9; max-width: 600px; margin: 0 auto 30px; }
        .search-box { max-width: 500px; margin: 0 auto; display: flex; }
        .search-input { flex: 1; padding: 12px 20px; border: none; border-radius: 25px 0 0 25px; font-size: 1rem; outline: none; }
        .search-btn { padding: 12px 25px; background: white; color: var(--primary); border: none; border-radius: 0 25px 25px 0; cursor: pointer; font-weight: 600; transition: transform 0.3s; }
        .search-btn:hover { transform: scale(1.05); }
        /* 分类标签 */
        .categories { display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin-bottom: 30px; padding: 0 20px; }
        .category-btn { padding: 8px 20px; background: white; border: 2px solid #ddd; border-radius: 20px; cursor: pointer; transition: all 0.3s; font-weight: 500; }
        .category-btn:hover, .category-btn.active { background: var(--primary); color: white; border-color: var(--primary); }
        /* 商品网格 */
        .products-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; padding: 0 20px; max-width: 1200px; margin: 0 auto; }
        .product-card { background: white; border-radius: 15px; overflow: hidden; box-shadow: 0 5px 20px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s; }
        .product-card:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(0,0,0,0.15); }
        .product-image { width: 100%; height: 200px; object-fit: cover; background: #f0f0f0; }
        .product-info { padding: 20px; }
        .product-title { font-size: 1.1rem; font-weight: 600; margin-bottom: 8px; color: var(--dark); line-height: 1.4; }
        .product-price { font-size: 1.4rem; font-weight: 700; color: var(--primary); margin-bottom: 15px; }
        .product-rating { color: #f39c12; margin-bottom: 15px; font-weight: 500; }
        .add-to-cart-btn { width: 100%; padding: 12px; background: var(--primary); color: white; border: none; border-radius: 8px; font-weight: 600; cursor: pointer; transition: background 0.3s; margin-bottom: 10px; }
        .add-to-cart-btn:hover { background: #e55a5a; }
        .product-actions { display: flex; gap: 10px; }
        .like-btn { flex: 1; padding: 10px; background: rgba(255,255,255,0.8); border: 2px solid #ddd; border-radius: 8px; cursor: pointer; font-weight: 500; transition: all 0.3s; display: flex; align-items: center; justify-content: center; gap: 5px; }
        .like-btn:hover { border-color: var(--primary); color: var(--primary); }
        .like-btn.liked { background: #ffe5e5; border-color: var(--primary); color: var(--primary); }
        .review-count { font-size: 0.85rem; color: #666; margin-bottom: 10px; cursor: pointer; transition: color 0.3s; }
        .review-count:hover { color: var(--primary); }
        /* 优惠券弹窗 */
        .coupon-modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 2000; justify-content: center; align-items: center; }
        .coupon-modal.show { display: flex; }
        .coupon-modal-content { background: white; border-radius: 20px; width: 90%; max-width: 500px; padding: 30px; position: relative; }
        .close-modal { position: absolute; top: 15px; right: 20px; font-size: 2rem; cursor: pointer; color: #999; }
        .close-modal:hover { color: var(--primary); }
        .coupon-header { font-size: 1.5rem; font-weight: 700; margin-bottom: 20px; color: var(--dark); border-bottom: 2px solid #eee; padding-bottom: 15px; }
        .coupon-input-group { display: flex; gap: 10px; margin-bottom: 20px; }
        .coupon-input { flex: 1; padding: 12px; border: 1px solid #ddd; border-radius: 8px; font-size: 1rem; }
        .apply-btn { padding: 12px 25px; background: var(--success); color: white; border: none; border-radius: 8px; font-weight: 600; cursor: pointer; transition: background 0.3s; }
        .apply-btn:hover { background: #219a52; }
        .coupon-list { margin-top: 20px; }
        .coupon-item { display: flex; justify-content: space-between; align-items: center; padding: 15px; background: #f9f9f9; border-radius: 10px; margin-bottom: 10px; }
        .coupon-item.used { opacity: 0.6; }
        .coupon-title { font-weight: 600; color: var(--dark); }
        .coupon-desc { font-size: 0.85rem; color: #666; }
        .coupon-value { color: var(--success); font-weight: 700; }
        /* 模态框 - 评论 */
        .review-modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 2000; justify-content: center; align-items: center; }
        .review-modal.show { display: flex; }
        .review-modal-content { background: white; border-radius: 20px; width: 90%; max-width: 600px; max-height: 80vh; overflow-y: auto; padding: 30px; position: relative; }
        .review-header { font-size: 1.5rem; font-weight: 700; margin-bottom: 20px; color: var(--dark); border-bottom: 2px solid #eee; padding-bottom: 15px; }
        .review-form { margin-bottom: 30px; }
        .form-group { margin-bottom: 15px; }
        .form-group label { display: block; margin-bottom: 5px; font-weight: 500; color: var(--dark); }
        .form-input, .form-textarea { width: 100%; padding: 10px; border: 1px solid #ddd; border-radius: 8px; font-size: 1rem; transition: border-color 0.3s; }
        .form-input:focus, .form-textarea:focus { outline: none; border-color: var(--primary); }
        .form-textarea { height: 100px; resize: vertical; }
        .submit-btn { width: 100%; padding: 12px; background: var(--success); color: white; border: none; border-radius: 8px; font-weight: 600; cursor: pointer; transition: background 0.3s; }
        .submit-btn:hover { background: #219a52; }
        .reviews-section { margin-top: 30px; }
        .reviews-title { font-size: 1.3rem; font-weight: 700; margin-bottom: 15px; color: var(--dark); }
        .review-item { background: #f9f9f9; padding: 15px; border-radius: 10px; margin-bottom: 15px; }
        .review-header-info { display: flex; justify-content: space-between; align-items: center; margin-bottom: 10px; }
        .review-author { font-weight: 600; color: var(--dark); }
        .review-date { font-size: 0.85rem; color: #999; }
        .review-stars { color: #f39c12; margin-bottom: 8px; }
        .review-text { line-height: 1.6; color: #555; margin-bottom: 10px; }
        .review-actions { display: flex; gap: 10px; }
        .like-review-btn { padding: 5px 10px; background: rgba(255,255,255,0.8); border: 1px solid #ddd; border-radius: 5px; cursor: pointer; font-size: 0.85rem; }
        .like-review-btn:hover { background: #ffe5e5; }
        .delete-review-btn { padding: 5px 10px; background: rgba(255,255,255,0.8); border: 1px solid #ddd; border-radius: 5px; cursor: pointer; font-size: 0.85rem; }
        .delete-review-btn:hover { background: #ffe5e5; color: #e74c3c; }
        .no-reviews { text-align: center; padding: 40px; color: #999; }
        /* 模态框 - 购物车 */
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 2000; justify-content: center; align-items: center; }
        .modal.show { display: flex; }
        .modal-content { background: white; border-radius: 20px; width: 90%; max-width: 600px; max-height: 80vh; overflow-y: auto; padding: 30px; position: relative; }
        .cart-header { font-size: 1.5rem; font-weight: 700; margin-bottom: 20px; color: var(--dark); border-bottom: 2px solid #eee; padding-bottom: 15px; }
        .cart-items { margin-bottom: 20px; }
        .cart-item { display: flex; justify-content: space-between; align-items: center; padding: 15px 0; border-bottom: 1px solid #eee; }
        .cart-item-info { flex: 1; margin-left: 15px; }
        .cart-item-title { font-weight: 600; margin-bottom: 5px; }
        .cart-item-price { color: var(--primary); font-weight: 600; }
        .remove-btn { background: none; border: none; color: #e74c3c; cursor: pointer; font-size: 1.2rem; padding: 0; }
        .cart-total { display: flex; justify-content: space-between; font-size: 1.2rem; font-weight: 700; margin-top: 20px; padding-top: 20px; border-top: 2px solid #eee; }
        .checkout-btn { width: 100%; padding: 15px; background: var(--success); color: white; border: none; border-radius: 10px; font-size: 1.1rem; font-weight: 600; cursor: pointer; margin-top: 20px; transition: background 0.3s; }
        .checkout-btn:hover { background: #219a52; }
        .empty-cart { text-align: center; padding: 40px; color: #999; }
        .empty-cart-icon { font-size: 4rem; margin-bottom: 15px; }
        /* 点赞统计区 */
        .site-like-section-page { text-align: center; margin: 30px 0; padding: 20px; background: white; border-radius: 15px; max-width: 600px; margin: 30px auto; box-shadow: 0 5px 20px rgba(0,0,0,0.05); }
        .site-like-section .emoji { font-size: 3rem; margin-bottom: 10px; }
        .site-like-section .text { font-size: 1.1rem; color: #666; margin-bottom: 15px; }
        .like-bar-container { width: 100%; height: 20px; background: #eee; border-radius: 10px; overflow: hidden; position: relative; }
        .like-bar-fill { height: 100%; background: linear-gradient(90deg, var(--primary), var(--secondary)); width: 0%; transition: width 0.5s ease; }
        .like-bar-text { position: absolute; width: 100%; text-align: center; top: 2px; font-size: 0.8rem; color: white; font-weight: 600; }
        /* 页面切换动画 */
        .page { display: none; animation: fadeIn 0.5s; }
        .page.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        /* 标签样式 */
        .new-tag { position: absolute; top: 10px; right: 10px; background: var(--success); color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8rem; font-weight: 600; }
        .sale-tag { position: absolute; top: 10px; right: 10px; background: #e74c3c; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8rem; font-weight: 600; }
        .product-card { position: relative; }
        /* 支付模态框 */
        .payment-modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 2000; justify-content: center; align-items: center; }
        .payment-modal.show { display: flex; }
        .payment-modal-content { background: white; border-radius: 20px; width: 90%; max-width: 500px; padding: 30px; position: relative; }
        .payment-title { font-size: 1.5rem; font-weight: 700; margin-bottom: 20px; color: var(--dark); border-bottom: 2px solid #eee; padding-bottom: 15px; }
        .payment-form { display: flex; flex-direction: column; gap: 15px; }
        .payment-form label { font-weight: 500; color: var(--dark); }
        .payment-form input, .payment-form select { padding: 12px; border: 1px solid #ddd; border-radius: 8px; font-size: 1rem; }
        .pay-btn { padding: 15px; background: var(--primary); color: white; border: none; border-radius: 10px; font-size: 1.1rem; font-weight: 600; cursor: pointer; transition: background 0.3s; }
        .pay-btn:hover { background: #e55a5a; }
        /* 打赏页面 */
        .donation-page { padding: 60px 20px; text-align: center; }
        .donation-card { background: white; border-radius: 20px; padding: 40px; max-width: 500px; margin: 0 auto; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        .donation-emoji { font-size: 5rem; margin-bottom: 20px; }
        .donation-title { font-size: 2rem; font-weight: 700; margin-bottom: 15px; color: var(--dark); }
        .donation-desc { color: #666; margin-bottom: 30px; line-height: 1.6; }
        .donation-amounts { display: flex; gap: 15px; justify-content: center; margin-bottom: 30px; flex-wrap: wrap; }
        .amount-btn { padding: 12px 25px; background: #f0f0f0; border: 2px solid transparent; border-radius: 10px; cursor: pointer; font-weight: 600; transition: all 0.3s; }
        .amount-btn:hover, .amount-btn.active { background: var(--primary); color: white; border-color: var(--primary); }
        .custom-amount { display: flex; gap: 10px; margin-bottom: 30px; }
        .custom-amount input { flex: 1; padding: 12px; border: 1px solid #ddd; border-radius: 8px; font-size: 1rem; }
        /* 成功提示 */
        .success-message { text-align: center; padding: 40px; color: var(--success); }
        .success-icon { font-size: 5rem; margin-bottom: 20px; }
        /* 反馈弹窗 */
        .feedback-modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 2000; justify-content: center; align-items: center; }
        .feedback-modal.show { display: flex; }
        .feedback-modal-content { background: white; border-radius: 20px; width: 90%; max-width: 500px; padding: 30px; position: relative; }
        .feedback-title { font-size: 1.5rem; font-weight: 700; margin-bottom: 20px; color: var(--dark); }
        .feedback-stars { display: flex; gap: 5px; justify-content: center; margin-bottom: 20px; }
        .feedback-star { font-size: 2rem; cursor: pointer; color: #ddd; transition: color 0.3s; }
        .feedback-star:hover, .feedback-star.active { color: #f39c12; }
        .feedback-input { width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 8px; font-size: 1rem; resize: vertical; min-height: 100px; }
        /* 响应式 */
        @media (max-width: 768px) { .nav-container { flex-direction: column; gap: 15px; } .nav-links { gap: 15px; } .hero h1 { font-size: 2rem; } }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav>
        <div class="nav-container">
            <div class="logo">🍅 番茄商城</div>
            <ul class="nav-links">
                <li><a href="#" class="nav-link active" data-page="home">首页</a></li>
                <li><a href="#" class="nav-link" data-page="electronics">电子产品</a></li>
                <li><a href="#" class="nav-link" data-page="clothing">服饰穿搭</a></li>
                <li><a href="#" class="nav-link" data-page="sports">运动健康</a></li>
                <li><a href="#" class="nav-link" data-page="home-deco">家居装饰</a></li>
                <li><a href="#" class="nav-link" data-page="books">图书音像</a></li>
                <li><a href="#" class="nav-link" data-page="toys">玩具益智</a></li>
                <li class="cart-icon" onclick="toggleCart()">🛒 <span class="cart-count" id="cartCount">0</span></li>
                <div class="site-like-section" onclick="toggleSiteLike();" style="cursor: pointer;">
                    <button class="site-like-button" id="siteLikeButton">♡</button>
                    <span class="site-like-count" id="siteLikeCount">0</span>
                </div>
            </ul>
        </div>
    </nav>

    <!-- 主内容区 -->
    <div class="main-content">
        <!-- 首页 -->
        <section id="home" class="page active">
            <div class="hero">
                <h1>欢迎来到番茄商城 🛍️</h1>
                <p>精选优质商品，品质生活从这里开始</p>
                <div class="search-box">
                    <input type="text" class="search-input" placeholder="搜索你想找的商品..." onkeyup="searchProducts(this.value)">
                    <button class="search-btn" onclick="searchProducts('')">搜索</button>
                </div>
            </div>

            <div class="categories">
                <button class="category-btn active" onclick="filterCategory('all')">全部商品</button>
                <button class="category-btn" onclick="filterCategory('electronics')">电子产品</button>
                <button class="category-btn" onclick="filterCategory('clothing')">服饰穿搭</button>
                <button class="category-btn" onclick="filterCategory('sports')">运动健康</button>
                <button class="category-btn" onclick="filterCategory('home-deco')">家居装饰</button>
                <button class="category-btn" onclick="filterCategory('books')">图书音像</button>
                <button class="category-btn" onclick="filterCategory('toys')">玩具益智</button>
            </div>

            <div class="products-grid" id="productsGrid"></div>
        </section>

        <!-- 各分类页面 -->
        <section id="electronics" class="page">
            <h2 style="text-align: center; margin: 30px 0; font-size: 2rem;">📱 电子产品</h2>
            <div class="products-grid" id="electronicsProducts"></div>
        </section>
        <section id="clothing" class="page">
            <h2 style="text-align: center; margin: 30px 0; font-size: 2rem;">👕 服饰穿搭</h2>
            <div class="products-grid" id="clothingProducts"></div>
        </section>
        <section id="sports" class="page">
            <h2 style="text-align: center; margin: 30px 0; font-size: 2rem;">🏃 运动健康</h2>
            <div class="products-grid" id="sportsProducts"></div>
        </section>
        <section id="home-deco" class="page">
            <h2 style="text-align: center; margin: 30px 0; font-size: 2rem;">🏠 家居装饰</h2>
            <div class="products-grid" id="homeDecoProducts"></div>
        </section>
        <section id="books" class="page">
            <h2 style="text-align: center; margin: 30px 0; font-size: 2rem;">📚 图书音像</h2>
            <div class="products-grid" id="booksProducts"></div>
        </section>
        <section id="toys" class="page">
            <h2 style="text-align: center; margin: 30px 0; font-size: 2rem;">🧸 玩具益智</h2>
            <div class="products-grid" id="toysProducts"></div>
        </section>
    </div>

    <!-- 网站点赞统计 -->
    <div class="site-like-section-page">
        <div class="emoji">👍</div>
        <div class="text">已为番茄商城点赞的用户数</div>
        <div class="like-bar-container">
            <div class="like-bar-fill" id="likeBar"></div>
            <div class="like-bar-text" id="likeBarText">0%</div>
        </div>
        <div style="margin-top: 15px; font-weight: 600; color: var(--primary);">总点赞数: <span id="totalLikes">0</span></div>
    </div>

    <!-- 优惠券弹窗 -->
    <div class="coupon-modal" id="couponModal">
        <div class="coupon-modal-content">
            <span class="close-modal" onclick="closeCouponModal()">&times;</span>
            <h2 class="coupon-header">🎁 输入优惠券</h2>
            <div class="coupon-input-group">
                <input type="text" class="coupon-input" id="couponCode" placeholder="请输入优惠券码">
                <button class="apply-btn" onclick="applyCoupon()">应用</button>
            </div>
            <div class="coupon-list" id="couponList"></div>
        </div>
    </div>

    <!-- 评论模态框 -->
    <div class="review-modal" id="reviewModal">
        <div class="review-modal-content">
            <span class="close-modal" onclick="closeReviewModal()">&times;</span>
            <h2 class="review-header">添加评论</h2>
            <div class="review-form">
                <div class="form-group">
                    <label>评论标题</label>
                    <input type="text" class="form-input" id="reviewTitle" placeholder="例如：很棒的商品！">
                </div>
                <div class="form-group">
                    <label>评论内容</label>
                    <textarea class="form-textarea" id="reviewText" placeholder="写下你的使用体验..."></textarea>
                </div>
                <div class="form-group">
                    <label>评分</label>
                    <div style="display: flex; gap: 5px;">
                        <span class="review-star" onclick="setRating(1)">★</span>
                        <span class="review-star" onclick="setRating(2)">★</span>
                        <span class="review-star" onclick="setRating(3)">★</span>
                        <span class="review-star" onclick="setRating(4)">★</span>
                        <span class="review-star" onclick="setRating(5)">★</span>
                    </div>
                </div>
                <button class="submit-btn" onclick="submitReview()">提交评论</button>
            </div>
        </div>
    </div>

    <!-- 购物车模态框 -->
    <div class="modal" id="cartModal">
        <div class="modal-content">
            <span class="close-modal" onclick="toggleCart()">&times;</span>
            <h2 class="cart-header">我的购物车</h2>
            <div class="cart-items" id="cartItems"></div>
            <div class="cart-total">
                <span>总计：</span>
                <span id="cartTotal" style="color: var(--primary);">¥0</span>
            </div>
            <div style="margin-top: 15px; display: flex; gap: 10px;">
                <button class="apply-btn" style="flex: 1;" onclick="openCouponModal()">优惠券</button>
                <button class="checkout-btn" onclick="checkout()">去结算</button>
            </div>
        </div>
    </div>

    <!-- 支付模态框 -->
    <div class="payment-modal" id="paymentModal">
        <div class="payment-modal-content">
            <span class="close-modal" onclick="closePaymentModal()">&times;</span>
            <h2 class="payment-title">📝 填写支付信息</h2>
            <div class="payment-form">
                <div>
                    <label>收货姓名</label>
                    <input type="text" placeholder="请输入姓名">
                </div>
                <div>
                    <label>联系电话</label>
                    <input type="tel" placeholder="请输入手机号">
                </div>
                <div>
                    <label>收货地址</label>
                    <input type="text" placeholder="请输入详细地址">
                </div>
                <div>
                    <label>支付方式</label>
                    <select>
                        <option>支付宝</option>
                        <option>微信支付</option>
                        <option>信用卡</option>
                    </select>
                </div>
                <button class="pay-btn" onclick="processPayment()">立即支付 ¥<span id="payAmount">0</span></button>
            </div>
        </div>
    </div>

    <!-- 打赏页面入口 -->
    <section id="donate" class="page">
        <div class="donation-page">
            <div class="donation-card">
                <div class="donation-emoji">🍅</div>
                <h2 class="donation-title">支持番茄商城</h2>
                <p class="donation-desc">如果觉得本站内容对你有帮助，欢迎打赏支持，让我们一起把番茄商城做得更好！</p>
                <div class="donation-amounts">
                    <button class="amount-btn" onclick="selectAmount(10)">¥10</button>
                    <button class="amount-btn" onclick="selectAmount(20)">¥20</button>
                    <button class="amount-btn" onclick="selectAmount(50)">¥50</button>
                    <button class="amount-btn" onclick="selectAmount(100)">¥100</button>
                    <button class="amount-btn" onclick="selectAmount(200)">¥200</button>
                </div>
                <div class="custom-amount">
                    <input type="number" id="customAmount" placeholder="自定义金额（元）" min="1" step="0.1">
                    <button class="apply-btn" onclick="selectCustomAmount()">确定</button>
                </div>
                <button class="pay-btn" style="width: 100%; margin-top: 20px;" onclick="processDonation()">立即打赏</button>
            </div>
        </div>
    </section>

    <!-- 反馈弹窗 -->
    <div class="feedback-modal" id="feedbackModal">
        <div class="feedback-modal-content">
            <span class="close-modal" onclick="closeFeedbackModal()">&times;</span>
            <h2 class="feedback-title">感谢您的支持！</h2>
            <p style="text-align: center; margin-bottom: 20px; color: #666;">请给我们一个评价</p>
            <div class="feedback-stars">
                <span class="feedback-star" onclick="setFeedbackStar(1)">★</span>
                <span class="feedback-star" onclick="setFeedbackStar(2)">★</span>
                <span class="feedback-star" onclick="setFeedbackStar(3)">★</span>
                <span class="feedback-star" onclick="setFeedbackStar(4)">★</span>
                <span class="feedback-star" onclick="setFeedbackStar(5)">★</span>
            </div>
            <textarea class="feedback-input" placeholder="写下您的建议..."></textarea>
            <button class="submit-btn" style="width: 100%; margin-top: 15px;" onclick="submitFeedback()">提交</button>
        </div>
    </div>

    <script>
        // 商品数据
        const products = [
            { id: 1, name: 'iPhone 15 Pro', price: 7999, category: 'electronics', rating: 4.8, image: 'https://picsum.photos/seed/iphone300/300', tag: 'new', reviews: [{ author: '张三', title: '性能好', text: '手机非常好用，运行流畅', rating: 5, likes: 12 }], likes: 8 },
            { id: 2, name: 'MacBook Air M2', price: 8999, category: 'electronics', rating: 4.9, image: 'https://picsum.photos/seed/macbook300/300', tag: '', reviews: [{ author: '李四', title: '轻薄便携', text: '非常轻便，续航很好', rating: 5, likes: 25 }], likes: 15 },
            { id: 3, name: 'Sony WH-1000XM5', price: 2499, category: 'electronics', rating: 4.7, image: 'https://picsum.photos/seed/headphones300/300', tag: 'sale', reviews: [], likes: 8 },
            { id: 4, name: 'iPad Air 5', price: 3999, category: 'electronics', rating: 4.6, image: 'https://picsum.photos/seed/ipad300/300', tag: '', reviews: [], likes: 5 },
            { id: 5, name: '智能手表 Series 9', price: 2499, category: 'electronics', rating: 4.5, image: 'https://picsum.photos/seed/watch300/300', tag: '', reviews: [], likes: 3 },
            { id: 6, name: '无线耳机 AirPods Pro 2', price: 1899, category: 'electronics', rating: 4.8, image: 'https://picsum.photos/seed/airpods300/300', tag: 'new', reviews: [], likes: 10 },
            { id: 7, name: '男士潮流 T 恤', price: 199, category: 'clothing', rating: 4.3, image: 'https://picsum.photos/seed/tshirt300/300', tag: '', reviews: [], likes: 2 },
            { id: 8, name: '时尚牛仔裤', price: 399, category: 'clothing', rating: 4.5, image: 'https://picsum.photos/seed/jeans300/300', tag: 'sale', reviews: [{ author: '王五', title: '版型好', text: '穿着很舒服，颜色正', rating: 4, likes: 8 }], likes: 12 },
            { id: 9, name: '运动卫衣外套', price: 499, category: 'clothing', rating: 4.4, image: 'https://picsum.photos/seed/hoodie300/300', tag: '', reviews: [], likes: 5 },
            { id: 10, name: '情侣装套装', price: 599, category: 'clothing', rating: 4.6, image: 'https://picsum.photos/seed/couple300/300', tag: '', reviews: [], likes: 7 },
            { id: 11, name: '时尚休闲鞋', price: 699, category: 'clothing', rating: 4.2, image: 'https://picsum.photos/seed/shoes300/300', tag: 'new', reviews: [], likes: 3 },
            { id: 12, name: '瑜伽垫健身套装', price: 299, category: 'sports', rating: 4.7, image: 'https://picsum.photos/seed/yoga300/300', tag: '', reviews: [], likes: 4 },
            { id: 13, name: '跑步机家用小型', price: 2999, category: 'sports', rating: 4.5, image: 'https://picsum.photos/seed/treadmill300/300', tag: '', reviews: [], likes: 2 },
            { id: 14, name: '智能跳绳', price: 199, category: 'sports', rating: 4.6, image: 'https://picsum.photos/seed/rope300/300', tag: 'new', reviews: [], likes: 1 },
            { id: 15, name: '智能手环健康监测', price: 399, category: 'sports', rating: 4.4, image: 'https://picsum.photos/seed/band300/300', tag: '', reviews: [], likes: 3 },
            { id: 16, name: '北欧风格吊灯', price: 899, category: 'home-deco', rating: 4.8, image: 'https://picsum.photos/seed/lamp300/300', tag: '', reviews: [], likes: 6 },
            { id: 17, name: '创意抱枕套装', price: 299, category: 'home-deco', rating: 4.6, image: 'https://picsum.photos/seed/pillow300/300', tag: 'sale', reviews: [], likes: 4 },
            { id: 18, name: '实木茶几', price: 1599, category: 'home-deco', rating: 4.7, image: 'https://picsum.photos/seed/table300/300', tag: '', reviews: [], likes: 3 },
            { id: 19, name: '艺术挂画装饰', price: 399, category: 'home-deco', rating: 4.5, image: 'https://picsum.photos/seed/art300/300', tag: 'new', reviews: [], likes: 2 },
            { id: 20, name: '智能音箱 HomePod', price: 799, category: 'home-deco', rating: 4.9, image: 'https://picsum.photos/seed/speaker300/300', tag: '', reviews: [], likes: 8 },
            { id: 21, name: '编程入门指南', price: 89, category: 'books', rating: 4.7, image: 'https://picsum.photos/seed/book300/300', tag: '', reviews: [{ author: '赵六', title: '实用性强', text: '很适合初学者，讲解清晰', rating: 5, likes: 15 }], likes: 20 },
            { id: 22, name: 'Python实战教程', price: 99, category: 'books', rating: 4.8, image: 'https://picsum.photos/seed/python300/300', tag: 'new', reviews: [{ author: '钱七', title: '很好', text: '例子很实用，学完能上手', rating: 5, likes: 32 }], likes: 45 },
            { id: 23, name: '设计心理学', price: 79, category: 'books', rating: 4.6, image: 'https://picsum.photos/seed/design300/300', tag: '', reviews: [], likes: 10 },
            { id: 24, name: '黑胶唱片机', price: 1599, category: 'books', rating: 4.9, image: 'https://picsum.photos/seed/record300/300', tag: '', reviews: [], likes: 8 },
            { id: 25, name: '乐高积木套装', price: 599, category: 'toys', rating: 4.8, image: 'https://picsum.photos/seed/lego300/300', tag: '', reviews: [{ author: '孙八', title: '孩子喜欢', text: '孩子很喜欢，拼装过程很有趣', rating: 5, likes: 22 }], likes: 30 },
            { id: 26, name: '智能机器人玩具', price: 1299, category: 'toys', rating: 4.7, image: 'https://picsum.photos/seed/robot300/300', tag: 'new', reviews: [], likes: 15 },
            { id: 27, name: '拼装模型', price: 299, category: 'toys', rating: 4.5, image: 'https://picsum.photos/seed/model300/300', tag: '', reviews: [], likes: 8 },
            { id: 28, name: '儿童益智拼图', price: 99, category: 'toys', rating: 4.6, image: 'https://picsum.photos/seed/puzzle300/300', tag: '', reviews: [], likes: 5 }
        ];

        // 优惠券配置
        const coupons = [
            { code: 'WELCOME10', name: '欢迎优惠', value: 10, type: 'fixed', minPurchase: 50, used: false },
            { code: 'SAVE20', name: '全场8折', value: 20, type: 'percent', minPurchase: 100, used: false },
            { code: 'FREESHIP', name: '免运费', value: 0, type: 'free', minPurchase: 0, used: false },
            { code: 'VIP50', name: 'VIP专享', value: 50, type: 'fixed', minPurchase: 500, used: false }
        ];

        let cart = [];
        let currentFilter = 'all';
        let currentReviewProductId = null;
        let currentRating = 5;
        let selectedDonationAmount = 0;
        let siteLikes = parseInt(localStorage.getItem('siteLikes') || '0');
        let liked = localStorage.getItem('siteLiked') === 'true';
        let activeCoupons = [];

        // 初始化
        function init() {
            renderProducts(products);
            renderCategoryProducts();
            updateCartCount();
            updateSiteLikeDisplay();
            renderCouponsList();
        }

        // 渲染商品
        function renderProducts(productList) {
            const grid = document.getElementById('productsGrid');
            grid.innerHTML = productList.map(product => `
                <div class="product-card">
                    ${product.tag === 'new' ? '<span class="new-tag">新品</span>' : product.tag === 'sale' ? '<span class="sale-tag">促销</span>' : ''}
                    <img src="${product.image}" alt="${product.name}" class="product-image">
                    <div class="product-info">
                        <div class="product-title">${product.name}</div>
                        <div class="product-rating">${'⭐'.repeat(Math.floor(product.rating))}${'★'.repeat(5-Math.floor(product.rating))} ${product.rating.toFixed(1)}</div>
                        <div class="product-price">¥${product.price.toLocaleString()}</div>
                        <div class="review-count" onclick="openReviewModal(${product.id})">已有 ${product.reviews.length} 条评论</div>
                        <button class="add-to-cart-btn" onclick="addToCart(${product.id})">加入购物车</button>
                        <div class="product-actions">
                            <button class="like-btn ${product.likes > 0 ? 'liked' : ''}" onclick="toggleProductLike(${product.id}); event.stopPropagation();">
                                ❤️ <span>${product.likes}</span>
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // 渲染分类商品
        function renderCategoryProducts() {
            document.getElementById('electronicsProducts').innerHTML = products.filter(p => p.category === 'electronics').map(p => createCardWithReviews(p)).join('');
            document.getElementById('clothingProducts').innerHTML = products.filter(p => p.category === 'clothing').map(p => createCardWithReviews(p)).join('');
            document.getElementById('sportsProducts').innerHTML = products.filter(p => p.category === 'sports').map(p => createCardWithReviews(p)).join('');
            document.getElementById('homeDecoProducts').innerHTML = products.filter(p => p.category === 'home-deco').map(p => createCardWithReviews(p)).join('');
            document.getElementById('booksProducts').innerHTML = products.filter(p => p.category === 'books').map(p => createCardWithReviews(p)).join('');
            document.getElementById('toysProducts').innerHTML = products.filter(p => p.category === 'toys').map(p => createCardWithReviews(p)).join('');
        }

        // 创建商品卡片（带评论）
        function createCardWithReviews(product) {
            const reviewCount = product.reviews.length;
            const reviewsHTML = reviewCount > 0 ? 
                `<div class="review-item" style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-radius: 8px; font-size: 0.85rem; max-height: 80px; overflow-y: auto;">
                    ${product.reviews.slice(0, 2).map(r => `<div style="margin-bottom: 8px;"><strong>${r.author}</strong> (${r.rating}★): "${r.text.substring(0, 30)}..."</div>`).join('')}
                    ${reviewCount > 2 ? `<div style="color: var(--primary); cursor: pointer;" onclick="openReviewModal(${product.id}); event.stopPropagation();">查看全部 ${reviewCount} 评论 →</div>` : ''}
                </div>` : '<div style="color: #999; font-size: 0.85rem; margin-top: 10px;">暂无评论，成为第一个评论者！</div>';

            return `
                <div class="product-card">
                    ${product.tag === 'new' ? '<span class="new-tag">新品</span>' : product.tag === 'sale' ? '<span class="sale-tag">促销</span>' : ''}
                    <img src="${product.image}" alt="${product.name}" class="product-image">
                    <div class="product-info">
                        <div class="product-title">${product.name}</div>
                        <div class="product-rating">${'⭐'.repeat(Math.floor(product.rating))}${'★'.repeat(5-Math.floor(product.rating))} ${product.rating.toFixed(1)}</div>
                        <div class="product-price">¥${product.price.toLocaleString()}</div>
                        <div class="review-count" onclick="openReviewModal(${product.id})">已有 ${reviewCount} 条评论</div>
                        <button class="add-to-cart-btn" onclick="addToCart(${product.id})">加入购物车</button>
                        <div class="product-actions">
                            <button class="like-btn ${product.likes > 0 ? 'liked' : ''}" onclick="toggleProductLike(${product.id}); event.stopPropagation();">
                                ❤️ <span>${product.likes}</span>
                            </button>
                        </div>
                        ${reviewsHTML}
                    </div>
                </div>
            `;
        }

        // 添加到购物车
        function addToCart(productId) {
            const product = products.find(p => p.id === productId);
            const existingItem = cart.find(item => item.id === productId);
            
            if (existingItem) {
                existingItem.quantity++;
            } else {
                cart.push({ ...product, quantity: 1 });
            }
            
            updateCartCount();
            showNotification(`${product.name} 已加入购物车`);
        }

        // 更新购物车数量
        function updateCartCount() {
            const totalCount = cart.reduce((sum, item) => sum + item.quantity, 0);
            const totalAmount = cart.reduce((sum, item) => sum + item.price * item.quantity, 0);
            document.getElementById('cartCount').textContent = totalCount;
            document.getElementById('cartTotal').textContent = '¥' + totalAmount.toLocaleString();
            renderCartItems();
        }

        // 渲染购物车项
        function renderCartItems() {
            const container = document.getElementById('cartItems');
            if (cart.length === 0) {
                container.innerHTML = '<div class="empty-cart"><div class="empty-cart-icon">🛒</div><div>购物车是空的，快去选购吧！</div></div>';
                return;
            }
            container.innerHTML = cart.map(item => `
                <div class="cart-item">
                    <div class="cart-item-info">
                        <div class="cart-item-title">${item.name}</div>
                        <div class="cart-item-price">¥${item.price} × ${item.quantity}</div>
                    </div>
                    <div style="display: flex; align-items: center; gap: 10px;">
                        <span>${item.quantity}</span>
                        <button class="remove-btn" onclick="removeFromCart(${item.id})">×</button>
                    </div>
                </div>
            `).join('');
        }

        // 从购物车移除
        function removeFromCart(productId) {
            cart = cart.filter(item => item.id !== productId);
            updateCartCount();
        }

        // 切换购物车显示
        function toggleCart() {
            const modal = document.getElementById('cartModal');
            modal.classList.toggle('show');
            if (modal.classList.contains('show')) {
                renderCartItems();
            }
        }

        // 结算
        function checkout() {
            if (cart.length === 0) {
                showNotification('购物车是空的！请先添加商品');
                return;
            }
            
            const total = cart.reduce((sum, item) => sum + item.price * item.quantity, 0);
            document.getElementById('payAmount').textContent = total.toLocaleString();
            document.getElementById('paymentModal').classList.add('show');
        }

        // 分类过滤
        function filterCategory(category) {
            currentFilter = category;
            
            document.querySelectorAll('.category-btn').forEach(btn => btn.classList.remove('active'));
            event.target.classList.add('active');
            
            const filtered = category === 'all' ? products : products.filter(p => p.category === category);
            renderProducts(filtered);
        }

        // 搜索
        function searchProducts(query) {
            if (!query.trim()) {
                renderProducts(currentFilter === 'all' ? products : products.filter(p => p.category === currentFilter));
                return;
            }
            const filtered = products.filter(p => p.name.toLowerCase().includes(query.toLowerCase()));
            renderProducts(filtered);
        }

        // 导航切换
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                
                document.querySelectorAll('.nav-link').forEach(l => l.classList.remove('active'));
                this.classList.add('active');
                
                document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
                
                const pageId = this.dataset.page;
                document.getElementById(pageId).classList.add('active');
                
                window.scrollTo({ top: 0, behavior: 'smooth' });
            });
        });

        // 通知提示
        function showNotification(message) {
            const notification = document.createElement('div');
            notification.style.cssText = `position: fixed; top: 100px; right: 20px; background: var(--success); color: white; padding: 15px 25px; border-radius: 10px; z-index: 3000; font-weight: 600; box-shadow: 0 5px 20px rgba(0,0,0,0.2);`;
            notification.textContent = message;
            document.body.appendChild(notification);
            setTimeout(() => notification.remove(), 3000);
        }

        // 点击模态框外部关闭
        document.getElementById('cartModal').addEventListener('click', function(e) {
            if (e.target === this) toggleCart();
        });

        // ===== 网站点赞系统 =====
        function toggleSiteLike() {
            const button = document.getElementById('siteLikeButton');
            const countDisplay = document.getElementById('siteLikeCount');
            
            if (!liked) {
                siteLikes++;
                liked = true;
                button.classList.add('liked');
                button.innerHTML = '❤️';
            } else {
                siteLikes--;
                liked = false;
                button.classList.remove('liked');
                button.innerHTML = '♡';
            }
            
            localStorage.setItem('siteLikes', siteLikes);
            localStorage.setItem('siteLiked', liked);
            updateSiteLikeDisplay();
        }

        function updateSiteLikeDisplay() {
            document.getElementById('siteLikeCount').textContent = siteLikes;
            document.getElementById('totalLikes').textContent = siteLikes;
            
            const maxTarget = 1000;
            const percentage = Math.min((siteLikes / maxTarget) * 100, 100);
            document.getElementById('likeBar').style.width = percentage + '%';
            document.getElementById('likeBarText').textContent = Math.round(percentage) + '%';
        }

        // ===== 优惠券系统 =====
        function openCouponModal() {
            document.getElementById('couponModal').classList.add('show');
            renderCouponsList();
        }

        function closeCouponModal() {
            document.getElementById('couponModal').classList.remove('show');
        }

        function applyCoupon() {
            const code = document.getElementById('couponCode').value.trim().toUpperCase();
            const coupon = coupons.find(c => c.code === code && !c.used);
            
            if (coupon) {
                coupon.used = true;
                activeCoupons.push(coupon);
                showNotification(`优惠券 ${coupon.name} 已应用！`);
                closeCouponModal();
                updateCartTotalWithCoupons();
            } else {
                showNotification('优惠券无效或已使用！');
            }
            document.getElementById('couponCode').value = '';
        }

        function renderCouponsList() {
            const container = document.getElementById('couponList');
            container.innerHTML = coupons.map(c => `
                <div class="coupon-item ${c.used ? 'used' : ''}">
                    <div>
                        <div class="coupon-title">${c.name}</div>
                        <div class="coupon-desc">${c.code}</div>
                    </div>
                    <div class="coupon-value">${c.type === 'percent' ? c.value + '% off' : '¥' + c.value}</div>
                </div>
            `).join('');
        }

        function updateCartTotalWithCoupons() {
            let total = cart.reduce((sum, item) => sum + item.price * item.quantity, 0);
            activeCoupons.forEach(coupon => {
                if (coupon.type === 'fixed') total -= coupon.value;
                if (coupon.type === 'percent') total = total * (1 - coupon.value / 100);
            });
            document.getElementById('cartTotal').textContent = '¥' + Math.max(0, total).toLocaleString();
        }

        // ===== 评论系统 =====
        function openReviewModal(productId) {
            currentReviewProductId = productId;
            document.getElementById('reviewModal').classList.add('show');
            document.getElementById('reviewTitle').value = '';
            document.getElementById('reviewText').value = '';
            setRating(5);
        }

        function closeReviewModal() {
            document.getElementById('reviewModal').classList.remove('show');
            currentReviewProductId = null;
        }

        function setRating(rating) {
            currentRating = rating;
            document.getElementById('reviewRating').value = rating;
            const stars = document.querySelectorAll('.review-star');
            stars.forEach((star, index) => {
                if (index < rating) {
                    star.style.color = '#f39c12';
                    star.style.textContent = '★';
                } else {
                    star.style.color = '#ddd';
                    star.style.textContent = '★';
                }
            });
        }

        function submitReview() {
            const title = document.getElementById('reviewTitle').value.trim();
            const text = document.getElementById('reviewText').value.trim();
            const rating = parseInt(document.getElementById('reviewRating').value);
            
            if (!title || !text) {
                showNotification('请填写完整的评论！');
                return;
            }
            
            const product = products.find(p => p.id === currentReviewProductId);
            if (product) {
                product.reviews.push({
                    author: '游客' + Math.floor(Math.random() * 1000),
                    title: title,
                    text: text,
                    rating: rating,
                    likes: 0,
                    date: new Date().toLocaleString('zh-CN')
                });
                renderCategoryProducts();
                closeReviewModal();
                showNotification('评论提交成功！');
            }
        }

        // ===== 商品点赞系统 =====
        function toggleProductLike(productId) {
            const product = products.find(p => p.id === productId);
            if (product) {
                product.likes++;
                renderProducts(currentFilter === 'all' ? products : products.filter(p => p.category === currentFilter));
                renderCategoryProducts();
            }
        }

        // ===== 支付系统 =====
        function processPayment() {
            const total = cart.reduce((sum, item) => sum + item.price * item.quantity, 0);
            showNotification(`支付 ¥${total.toLocaleString()} 成功！订单正在处理中...`);
            closePaymentModal();
            cart = [];
            updateCartCount();
            
            // 跳转到反馈页面
            setTimeout(() => {
                openFeedbackModal();
            }, 1500);
        }

        function closePaymentModal() {
            document.getElementById('paymentModal').classList.remove('show');
        }

        // ===== 打赏系统 =====
        function selectAmount(amount) {
            selectedDonationAmount = amount;
            document.getElementById('customAmount').value = amount;
            
            document.querySelectorAll('.amount-btn').forEach(btn => btn.classList.remove('active'));
            event.target.classList.add('active');
        }

        function selectCustomAmount() {
            const amount = parseFloat(document.getElementById('customAmount').value);
            if (amount && amount > 0) {
                selectedDonationAmount = amount;
                document.querySelectorAll('.amount-btn').forEach(btn => btn.classList.remove('active'));
            } else {
                showNotification('请输入有效的金额！');
            }
        }

        function processDonation() {
            if (!selectedDonationAmount || selectedDonationAmount <= 0) {
                showNotification('请选择打赏金额！');
                return;
            }
            
            showNotification(`打赏 ¥${selectedDonationAmount} 成功！感谢您的支持！`);
            selectedDonationAmount = 0;
            document.getElementById('customAmount').value = '';
            
            // 跳转到反馈
            setTimeout(() => {
                openFeedbackModal();
            }, 1000);
        }

        // ===== 反馈系统 =====
        let feedbackStars = 0;

        function openFeedbackModal() {
            document.getElementById('feedbackModal').classList.add('show');
            feedbackStars = 0;
            document.querySelectorAll('.feedback-star').forEach(star => star.classList.remove('active'));
        }

        function closeFeedbackModal() {
            document.getElementById('feedbackModal').classList.remove('show');
        }

        function setFeedbackStar(stars) {
            feedbackStars = stars;
            document.querySelectorAll('.feedback-star').forEach((star, index) => {
                if (index < stars) {
                    star.classList.add('active');
                } else {
                    star.classList.remove('active');
                }
            });
        }

        function submitFeedback() {
            if (feedbackStars === 0) {
                showNotification('请先选择星级评价！');
                return;
            }
            show反馈已提交，我们会改进！');
            closeFeedbackModal();
        }

        // 点击模态框外部关闭
        document.getElementById('couponModal').addEventListener('click', function(e) {
            if (e.target === this) closeCouponModal();
        });

        document.getElementById('reviewModal').addEventListener('click', function(e) {
            if (e.target === this) closeReviewModal();
        });

        document.getElementById('paymentModal').addEventListener('click', function(e) {
            if (e.target === this) closePaymentModal();
        });

        // 页面加载时初始化
        init();
    </script>
</body>
</html>
