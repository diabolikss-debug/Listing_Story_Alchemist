# Listing Story Alchemist

**Turn a product photo or one-line description into a complete, story-driven listing package.**

A Claude Skill that generates emotion-first, SEO-optimized product listings for Etsy and Gumroad sellers. Instead of writing generic product descriptions, it crafts narrative-driven copy that makes buyers feel something before they click "Add to Cart."

## What It Does

You give it a product photo or a simple description like:

> "handmade macrame wall hanging, boho style, natural cotton"

It gives you back a complete listing package with 7 sections:

| Section | What You Get |
|---|---|
| **Story Listing** | Emotion-driven product description with hook, bridge, details, and closing |
| **SEO Package** | Platform-optimized title + description + 13 strategic tags |
| **2X Favorite Version** | Premium rewrite with stronger hooks, scarcity, and identity positioning |
| **A/B Test Variants** | Two alternative title + opening combos to test different angles |
| **Seasonal Adaptation** | Current-season angles and optimal relaunch windows |
| **Competitor Analysis** | Search terms, differentiation angles, common category mistakes |
| **Pricing Insight** | Price range with reasoning, tier logic, and bundling potential |

## Supported Platforms

- **Etsy** (title format, 13-tag system, tag deduplication rules)
- **Gumroad** (short description field, markdown support, digital product focus)

## Output Language

English only.

## Installation

### Claude Desktop / Claude Code

Drop the `listing-story-alchemist/` folder into your skills directory:

```
~/.claude/skills/listing-story-alchemist/
```

### Manual

Copy `SKILL.md` into your Claude skill configuration.

## Usage Examples

**From a product photo:**
> "Here's a photo of my ceramic mug. Create an Etsy listing for it."

**From a text description:**
> "I sell a Notion template for freelancers to track invoices and clients. Write a Gumroad listing."

**Improving an existing listing:**
> "Here's my current Etsy listing for handmade earrings. Make it better."

**Platform-specific:**
> "Write an Etsy listing with all 13 tags for my watercolor print set."

## Writing Philosophy

The skill follows these principles:

- **Buyers buy feelings, not features.** Every listing starts with an emotional scene, not a product pitch.
- **SEO and emotion are partners, not opposites.** Keywords are woven into natural copy.
- **Specific beats vague.** "Hand-knotted with 4mm Egyptian cotton rope" always wins over "made with premium materials."
- **No AI-sounding language.** The output avoids words like "delve," "elevate," "curated," "bespoke," and other patterns that signal machine-generated text.
- **No em dashes.** Consistent with the author's style preferences.

## Product Type Coverage

Works with any product type, with specialized handling for:
- Physical handmade goods (jewelry, textiles, ceramics)
- Digital products (templates, printables, ebooks)
- Art and prints
- Vintage and curated items

## File Structure

```
listing-story-alchemist/
+-- SKILL.md          # Main skill instructions
+-- README.md         # This file
+-- LICENSE           # MIT License
+-- examples/
    +-- macrame.md    # Example: physical handmade product
    +-- notion.md     # Example: digital product (Gumroad)
```

## Contributing

Issues and pull requests welcome. If you sell on a platform not covered (Creative Market, Amazon Handmade, etc.), open an issue with platform-specific requirements and I'll consider adding support.

## License

MIT License. See [LICENSE](LICENSE) for details.

## Author

Created by [Diabolikss](https://github.com/diabolikss)

Part of the Diabolikss digital product toolkit.
