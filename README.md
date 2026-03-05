
# Shopify Theme Development - Dawn-Based Theme

## Orangy
Đây là 1 project với mục đích tự học tập và thực hành tạo 1 trang website dựa theo yêu cầu và design figma có sẵn trên nền tảng shopify. Project được tạo ra với mục đích cải thiện kỹ năng thao tác với Framework Shopify và không được sử dụng với mục đích thương mại. Project được dựa theo figma để làm theo tỉ lệ gần với design figma nhất có thể

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

1. **Clone or download**: `git clone https://github.com/hieu7654321/VuMinhHieu-2.git`
2. **Install dependencies**: `npm install`
3. **Connect to Shopify**: Configure `shopify.app.toml`
4. **Start development**: `npm run dev`
5. **Pull change from editor**: `npm run pull`

## Customization
- Edit Liquid files in `sections/` and `snippets/`
- Modify styles in `assets/`
- Update theme settings in `config/settings_schema.json`

## Requirements
- Shopify CLI
- Node.js 14+
- A Shopify development store
