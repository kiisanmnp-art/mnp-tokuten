<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MNP特典30選 - きいさん無料コンサル</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Hiragino Sans', 'Hiragino Kaku Gothic ProN', 'Yu Gothic', 'Meiryo', sans-serif;
            background: linear-gradient(135deg, #f6d365 0%, #fda085 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            width: 1200px;
            background: linear-gradient(135deg, #FFD700 0%, #FFA500 50%, #FF8C00 100%);
            border-radius: 30px;
            padding: 40px 50px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            position: relative;
            overflow: hidden;
        }

        /* キラキラエフェクト */
        .sparkle {
            position: absolute;
            width: 8px;
            height: 8px;
            background: white;
            border-radius: 50%;
            animation: sparkle 2s infinite;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.8);
        }

        @keyframes sparkle {
            0%, 100% { opacity: 0; transform: scale(0); }
            50% { opacity: 1; transform: scale(1); }
        }

        .sparkle:nth-child(1) { top: 10%; left: 15%; animation-delay: 0s; }
        .sparkle:nth-child(2) { top: 25%; right: 20%; animation-delay: 0.5s; }
        .sparkle:nth-child(3) { bottom: 30%; left: 10%; animation-delay: 1s; }
        .sparkle:nth-child(4) { bottom: 15%; right: 15%; animation-delay: 1.5s; }
        .sparkle:nth-child(5) { top: 50%; left: 5%; animation-delay: 0.3s; }
        .sparkle:nth-child(6) { top: 40%; right: 8%; animation-delay: 0.8s; }

        /* 星の装飾 */
        .star {
            position: absolute;
            font-size: 24px;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .star:nth-child(7) { top: 15%; left: 5%; animation-delay: 0s; }
        .star:nth-child(8) { top: 20%; right: 5%; animation-delay: 1s; }
        .star:nth-child(9) { bottom: 20%; left: 8%; animation-delay: 0.5s; }
        .star:nth-child(10) { bottom: 25%; right: 6%; animation-delay: 1.5s; }

        .header {
            text-align: center;
            margin-bottom: 30px;
            position: relative;
            z-index: 10;
        }

        .header h1 {
            font-size: 42px;
            font-weight: 900;
            color: #fff;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.3);
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        .header .subtitle {
            font-size: 18px;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            font-weight: 600;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px 25px;
            position: relative;
            z-index: 10;
        }

        .benefit-item {
            background: rgba(255, 255, 255, 0.95);
            padding: 12px 18px;
            border-radius: 15px;
            display: flex;
            align-items: flex-start;
            gap: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .benefit-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
        }

        .gift-icon {
            font-size: 20px;
            flex-shrink: 0;
            margin-top: 2px;
        }

        .benefit-number {
            font-size: 16px;
            font-weight: 800;
            color: #FF6B00;
            flex-shrink: 0;
            min-width: 35px;
        }

        .benefit-text {
            font-size: 14px;
            line-height: 1.5;
            color: #333;
            font-weight: 600;
        }

        .section-divider {
            grid-column: 1 / -1;
            height: 2px;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.6), transparent);
            margin: 10px 0;
        }

        .section-title {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 20px;
            font-weight: 800;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            padding: 8px 0;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- キラキラエフェクト -->
        <div class="sparkle"></div>
        <div class="sparkle"></div>
        <div class="sparkle"></div>
        <div class="sparkle"></div>
        <div class="sparkle"></div>
        <div class="sparkle"></div>
        
        <!-- 星の装飾 -->
        <div class="star">⭐</div>
        <div class="star">✨</div>
        <div class="star">⭐</div>
        <div class="star">✨</div>

        <div class="header">
            <h1>🎁 豪華特典30選 🎁</h1>
            <div class="subtitle">きいさん無料コンサル × MNP完全攻略パック</div>
        </div>

        <div class="benefits-grid">
            <!-- アテナさん特典 1-7 -->
            <div class="section-title">✨ アテナさん特典（1〜7）✨</div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">01.</span>
                <span class="benefit-text">完全初心者でも一撃25万稼げるスターター副業パック</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">02.</span>
                <span class="benefit-text">0からスタートで50万円作る具体的な手順大公開</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">03.</span>
                <span class="benefit-text">【40分の生音声】スマホで約5億円マネタイズした努力と葛藤の裏側大公開</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">04.</span>
                <span class="benefit-text">【光×MNP】Wi-Fi契約で爆益！MNPとの錬金術＋30万円術</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">05.</span>
                <span class="benefit-text">【1%の人しか知らない】MNP下取り裏技 利益を底上げする上級者テク</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">06.</span>
                <span class="benefit-text">MNPで必須知識！携帯の全キャリアの基本ルール＆利益計算動画解説</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">07.</span>
                <span class="benefit-text">家電量販店ポイントを最大利益で現金化する方法💰</span>
            </div>

            <div class="section-divider"></div>

            <!-- きいさんオリジナル特典 8-30 -->
            <div class="section-title">⚡ きいさんオリジナル特典（8〜30）⚡</div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">08.</span>
                <span class="benefit-text">【MNP弾作成】音声SIM最安維持費ランキングTOP10＆運用シート</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">09.</span>
                <span class="benefit-text">キャリア決算期を狙い撃ち！年間MNP最強カレンダー2025-2026</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">10.</span>
                <span class="benefit-text">複数回線同時MNPで"まとめて割増"を引き出す交渉術</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">11.</span>
                <span class="benefit-text">審査落ち経験者が語る！MNP契約審査を100%通すチェックリスト</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">12.</span>
                <span class="benefit-text">端末転売ヤーと間違われない"健全MNP"の立ち回り完全版</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">13.</span>
                <span class="benefit-text">eSIM×MNPの新常識！即日開通＆デュアル運用マスターガイド</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">14.</span>
                <span class="benefit-text">【実録データ】3大キャリアMNP引き止めポイント平均額＆交渉トーク集</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">15.</span>
                <span class="benefit-text">名義変更×MNP最適ルート！家族間で損しない完璧タイミング表</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">16.</span>
                <span class="benefit-text">ahamo/povo/LINEMO徹底比較！MNP時の隠れメリット＆デメリット全網羅</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">17.</span>
                <span class="benefit-text">楽天モバイル"1円運用"からの最強MNP出口戦略【2025最新版】</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">18.</span>
                <span class="benefit-text">iPhone実質1円の罠を見破る！本当の総額計算シミュレーター</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">19.</span>
                <span class="benefit-text">MNP予約番号有効期限ギリギリ活用術！15日を最大化するテクニック</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">20.</span>
                <span class="benefit-text">【禁断の情報】都道府県別MNP高額CB店舗マップ＆口コミデータベース</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">21.</span>
                <span class="benefit-text">ブラックリスト判定セルフチェック！CICスコア改善3ヶ月プログラム</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">22.</span>
                <span class="benefit-text">短期解約ペナルティ完全回避マニュアル【キャリア別ボーダーライン一覧】</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">23.</span>
                <span class="benefit-text">UQモバイル×auサブブランド間"特殊MNP"で二度おいしい錬金術</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">24.</span>
                <span class="benefit-text">5G対応エリア実測マップ！MNP前に絶対確認すべきスポット情報</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">25.</span>
                <span class="benefit-text">SIMロック解除＆端末残債一括精算の最適タイミング診断チャート</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">26.</span>
                <span class="benefit-text">法人契約×個人MNPのグレーゾーン完全整理【2025法改正対応版】</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">27.</span>
                <span class="benefit-text">キャリアメール持ち運びサービス徹底比較＆年間コスト最小化術</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">28.</span>
                <span class="benefit-text">MNP×ふるさと納税ポイント爆増テクニック【自治体別還元率リスト】</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">29.</span>
                <span class="benefit-text">【YouTube級】MNP実況解説動画30本＆失敗例から学ぶケーススタディ</span>
            </div>
            
            <div class="benefit-item">
                <span class="gift-icon">🎁</span>
                <span class="benefit-number">30.</span>
                <span class="benefit-text">MNP履歴管理スプレッドシート！利益計算・次回タイミング自動通知機能付き</span>
            </div>
        </div>
    </div>
</body>
</html>
