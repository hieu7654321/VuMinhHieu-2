
# Shopify Theme Development - Dawn-Based Theme

## Orangy
Đây là 1 project với mục đích thực hành tạo 1 trang website dựa theo yêu cầu và design figma có sẵn trên nền tảng shopify. Project được dựa theo figma để làm theo tỉ lệ gần với design figma nhất có thể

## Project Structure
```
├── assets/          # CSS, JS, ảnh
├── config/          # Theme settings & menus
├── layout/          # Base page layouts
├── sections/        # Customizable sections
├── snippets/        # Reusable components
└── templates/       # Page templates
```

## Getting Started

1. **Clone or download** this theme
2. **Install dependencies**: `npm install`
3. **Connect to Shopify**: Configure `shopify.app.toml`
4. **Start development**: `npm run dev`
5. **Deploy**: `npm run deploy`

## Customization
- Edit Liquid files in `sections/` and `snippets/`
- Modify styles in `assets/`
- Update theme settings in `config/settings_schema.json`

## Requirements
- Shopify CLI
- Node.js 14+
- A Shopify development store
