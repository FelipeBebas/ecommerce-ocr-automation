# ecommerce-ocr-automation
An automated AI workflow built with n8n to process complex PDF catalogs using GPT-4 Vision/OCR, extract unstructured data into CSV, and calculate dynamic B2B e-commerce margins via Telegram.

## 📖 The Story & The Problem

Imagine running a high-volume e-commerce operation, selling electronics on multiple marketplaces like Mercado Livre and Shopee. Your success depends on buying the right products at the right time.

Every week, your overseas suppliers send you a new product catalog. But there's a catch: it's a massive, 30-page PDF document. 

To place an order, you have to manually:
1. Scroll through hundreds of items visually.
2. Spot which products are "out of stock" (often indicated only by a visual watermark over the image).
3. Type out the current prices vs. the crossed-out original prices.
4. Open a spreadsheet to calculate complex margins, factoring in the specific commission fees, taxes, and shipping costs of *each* marketplace you sell on.
5. Manually type a WhatsApp message to the supplier formatting your entire order.

This process takes hours, is highly prone to human error, and delays purchasing decisions—meaning by the time you figure out what's profitable, the supplier might have already run out of stock.

**The Solution?** An automated n8n workflow that uses GPT-4 Vision to "read" the PDF, extract structured data, calculate margins instantly via Google Sheets, and serve everything through an interactive Telegram Bot.
