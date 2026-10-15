# Sample Data - Shopee Taiwan Product

This is an example of the data structure you'll receive for each product.

```json
{
  "item": {
    "itemid": 43507977449,
    "shopid": 50662979,
    "title": "威剛 高耐用 microSDXC UHS-I U3 A2 V30監控記憶卡64G/128G(附轉卡)",
    "price": 79900000,
    "price_max": 149900000,
    "price_min": 79900000,
    "currency": "TWD",
    "stock": 9876,
    "sold": 12345,
    "ctime": 1678901234,
    "brand": "Adata",
    "liked_count": 234,
    "view_count": 45678,
    "cmt_count": 891,
    "item_status": "normal",
    "has_low_stock_risk": false,
    "show_free_shipping": true,
    
    "item_rating": {
      "rating_star": 4.977049180327869,
      "rating_count": [891, 12, 8, 5, 34, 832],
      "rcount_with_context": 450,
      "rcount_with_image": 120
    },
    
    "images": [
      "sg-11134301-7rdyd-mbqjry195dif45",
      "sg-11134301-7rdyd-mbqjry19bne892",
      "sg-11134301-7rdyd-mbqjry19dfyc23"
    ],
    
    "image": "sg-11134301-7rdyd-mbqjry195dif45",
    "thumbnail": "sg-11134301-7rdyd-mbqjry195dif45",
    
    "discount": "-47%",
    "raw_discount": 47,
    "is_official_shop": false,
    "is_shopee_verified": false,
    "is_cc_installment_payment_eligible": true,
    
    "attributes": [
      {
        "idx": 0,
        "name": "記憶卡類型",
        "value": "Micro SD卡"
      },
      {
        "idx": 1,
        "name": "容量",
        "value": "64GB"
      },
      {
        "idx": 2,
        "name": "保固種類",
        "value": "原廠保固"
      },
      {
        "idx": 3,
        "name": "保固期限",
        "value": "終身保固"
      }
    ],
    
    "description": "【高耐用記憶卡】\n專為監控系統設計\n耐高低溫 防水防震\nUHS-I U3 A2 V30\n讀取速度: 100MB/s\n寫入速度: 30MB/s\n\n【產品規格】\n容量: 64GB / 128GB\n尺寸: microSD\n附轉卡\n原廠終身保固\n\n【適用設備】\n監控攝影機\n行車記錄器\n安全監視器\n智慧門鈴\n\n【蝦皮直營】\n正品保證 快速出貨",
    
    "size_chart": null,
    "condition": 1,
    "catid": 11012345,
    "category_path": "3C > 記憶卡 > microSD",
    
    "models": [
      {
        "itemid": 43507977449,
        "modelid": 123456789012,
        "name": "64GB",
        "price": 79900000,
        "stock": 5432,
        "sold": 7890
      },
      {
        "itemid": 43507977449,
        "modelid": 123456789013,
        "name": "128GB",
        "price": 149900000,
        "stock": 4444,
        "sold": 4455
      }
    ],
    
    "tier_variations": [
      {
        "name": "容量",
        "options": ["64GB", "128GB"],
        "images": []
      }
    ],
    
    "shop_location": "臺南市安南區",
    "shipping_fee_info": {
      "free_shipping": false,
      "estimated_shipping_fee": 0
    },
    
    "wholesale_tier_list": [],
    "bundle_deal_info": null,
    
    "coin_earn_label": "賺5%蝦幣",
    "coin_earn_info": {
      "coin_earn_rate": 0.05
    }
  },
  
  "shop": {
    "shopid": 50662979,
    "name": "蝦皮直營 3C旗艦館",
    "account": {
      "total_count": 891,
      "show_official_shop_label": false,
      "portrait": "tw-11134301-7rdyd-shop-portrait"
    },
    "item_count": 234,
    "follower_count": 12345,
    "rating_star": 4.9,
    "rating_normal": 4.85,
    "response_rate": 98,
    "response_time": 120,
    "is_official_shop": false,
    "is_shopee_verified": true,
    "vacation": false,
    "place": "臺南市"
  }
}
```

## Data Points Included

### Product Info (25+ fields)
- ID, name, brand, category
- Pricing (current, min, max, discount)
- Inventory (stock, sold count)
- Images (multiple angles)
- Description (full text)
- Attributes/specifications
- Condition, status

### Ratings & Reviews (10+ fields)
- Overall star rating
- Rating distribution (1-5 stars)
- Total review count
- Reviews with images/context
- Like count, view count

### Shop Info (15+ fields)
- Shop name, ID, location
- Shop ratings & response metrics
- Item count, follower count
- Verification badges
- Response time

### Pricing & Promotions
- Current price
- Original price (if discounted)
- Discount percentage
- Wholesale tiers
- Bundle deals
- Coin cashback

### Variations
- Model variants (size, color, etc.)
- Price per variant
- Stock per variant
- Sold count per variant

### Shipping
- Shipping fee
- Free shipping eligibility
- Estimated delivery

---

**Total: 80+ data points per product**

All fields are extracted from the official Shopee mobile API — the same data users see in the app.
