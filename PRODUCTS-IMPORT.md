# Sample Products Import Guide

## Importing sample-products.csv into Shopify

1. **Go to Shopify Admin** → Products → Import
2. **Upload** the `sample-products.csv` file
3. **Map columns** if prompted (the CSV uses standard Shopify headers including Image Src)
4. **Review** and click "Import products"

Shopify will download and host all images from the Unsplash URLs during import.

## Products Included (20 items)

| # | Product | Price (INR) | Type | Image |
|---|---------|-------------|------|-------|
| 1 | Premium Leather Dog Collar | ₹1,499 | Dog Collars | ✓ |
| 2 | Orthopedic Memory Foam Pet Bed | ₹3,999 | Pet Beds | ✓ |
| 3 | Interactive Feather Wand Toy Set | ₹599 | Cat Toys | ✓ |
| 4 | Stainless Steel Bowl Set (2-Pack) | ₹899 | Feeding | ✓ |
| 5 | Premium Dog Harness with Padded Chest | ₹1,899 | Dog Harnesses | ✓ |
| 6 | Cat Collar with Safety Bell | ₹349 | Cat Collars | ✓ |
| 7 | Pet Grooming Brush Set | ₹749 | Grooming | ✓ |
| 8 | Dog Treat Pouch with Dispenser | ₹549 | Training | ✓ |
| 9 | Rope Tug Toy for Dogs | ₹449 | Dog Toys | ✓ |
| 10 | Cat Scratching Post with Toy | ₹1,299 | Cat Furniture | ✓ |
| 11 | Portable Pet Water Bottle | ₹499 | Travel | ✓ |
| 12 | Elevated Feeder Set for Dogs | ₹2,499 | Feeding | ✓ |
| 13 | Soft-Sided Pet Carrier Bag | ₹1,899 | Travel | ✓ |
| 14 | Natural Dental Chew Sticks (6-Pack) | ₹699 | Dog Treats | ✓ |
| 15 | Cozy Cat Bed Cave | ₹1,299 | Cat Beds | ✓ |
| 16 | Reflective Dog Leash (5ft) | ₹649 | Dog Accessories | ✓ |
| 17 | Oatmeal Pet Shampoo (500ml) | ₹449 | Grooming | ✓ |
| 18 | Bird Perch & Play Stand | ₹1,999 | Bird Supplies | ✓ |
| 19 | Pet First Aid Kit | ₹999 | Health | ✓ |
| 20 | Slow Feeder Bowl for Dogs | ₹599 | Feeding | ✓ |

## Homepage Usage

After import, the **Bestsellers** section on the homepage will automatically show real products:

- **Product 1:** luxury-leather-dog-collar
- **Product 2:** orthopedic-memory-foam-pet-bed
- **Product 3:** interactive-feather-wand-cat-toy
- **Product 4:** stainless-steel-bowl-set-2pack

The theme uses product handles to display actual product data (title, price, image) — no more placeholder or test products.

## Collections Setup (Optional)

Create these collections in Shopify Admin → Products → Collections to organize products:

| Collection | Condition | Products |
|------------|-----------|----------|
| **Dogs** | Product tag contains `dogs` | ~12 products |
| **Cats** | Product tag contains `cats` | ~8 products |
| **Bestsellers** | Product tag contains `bestseller` | 4 products |
| **Birds** | Product tag contains `birds` | 1 product |

## Notes

- **Currency:** Prices are in Indian Rupees (INR). Set your store currency to INR in Settings → Store details.
- **Images:** All products include Unsplash image URLs (free to use). Shopify downloads and hosts them during import.
- **Product handles:** Used in the theme (e.g. `luxury-leather-dog-collar`). Do not change handles after import if you want the homepage to display correctly.
