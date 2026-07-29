---
name: rongjie-amazon-design
description: Create, plan, write, generate, polish, or audit Amazon product main images, secondary listing images, and A+/detail-page creative using Tang Rongjie's Amazon image commerce workflow. Use when the user asks for Amazon hero/main image concepts, image set strategy, listing infographic copy, comparison modules, lifestyle scene planning, A+ content structure, Chinese-English Amazon creative prompts, marketplace-safe claim handling, product-image-based visual direction, or final QA for Amazon product image and detail-page assets.
---

# Amazon 主图与详情页创作

## Overview

Use this skill to turn product photos, competitor references, and selling points into Amazon-ready main image and detail-page creative. The method belongs to Tang Rongjie and focuses on marketplace compliance, buyer evidence, image-set sequencing, and bilingual production clarity.

## Core Rule

Treat Amazon creative as a selling system, not isolated posters. Each image must answer one buyer question, support a claim with visible or supplied evidence, and fit the listing sequence.

Never invent certifications, measured parameters, medical effects, safety claims, compatibility, awards, discounts, or brand partnerships. If a claim is inferred from the product category, mark it as inferred and ask the user to confirm before commercial use.

## Workflow

1. Read the inputs

   Separate:

   - `observed_facts`: visible shape, color, material, package, accessories, UI, labels, quantity, and scale cues.
   - `provided_facts`: brand, title, specs, target market, platform, keywords, legal claims, and required copy.
   - `buyer_questions`: what shoppers must understand before clicking or buying.
   - `risk_claims`: anything that needs proof or should be softened.

2. Build the Amazon Image Matrix

   Plan the image set before generating or designing final assets. Include:

   - `image_id`
   - `slot_type`: main_image, secondary_image, lifestyle, infographic, comparison, instructions, trust, A_plus_module, closing
   - `buyer_question`
   - `evidence_anchor`
   - `main_message`
   - `visible_copy_en`
   - `visible_copy_zh`
   - `visual_direction`
   - `composition_notes`
   - `compliance_note`

   Ask for approval before producing final images when the user expects generated or designed assets.

3. Main image direction

   For Amazon main images:

   - Use a clean product-first composition.
   - Keep the product identity, color, shape, packaging, and included accessories accurate.
   - Avoid unsupported badges, excessive props, misleading scale, fake bundles, fake certification marks, and text-heavy poster treatment unless the target marketplace/category permits it.
   - Make the thumbnail readable: strong silhouette, clean edges, honest quantity, and clear product angle.

4. Secondary image direction

   Use the secondary image set to answer buyer questions in order:

   - What is included?
   - What problem does it solve?
   - How is it used?
   - What details or materials matter?
   - Why is it trustworthy?
   - How does it compare or fit?
   - What should the buyer remember before purchasing?

   Vary the format across images: infographic, close-up annotation, lifestyle scene, scale reference, setup steps, comparison, package contents, and trust notes.

5. A+ / detail-page direction

   For A+ or long detail pages, build modules instead of poster slices:

   - brand/product opening
   - benefit proof module
   - detail close-up module
   - scenario module
   - comparison or compatibility module
   - specification module
   - trust or care module
   - closing CTA-style reminder without unsupported urgency

6. Produce staged outputs

   When generating visuals, create the first 1-2 images or modules first. Inspect them for product drift, unreadable text, repeated layout, weak Amazon thumbnail performance, and unsupported claims. Continue only after the sample direction is acceptable.

7. Audit before delivery

   Check:

   - Main image is product-led and marketplace-safe.
   - Each secondary image has a different job.
   - Visible copy is short, readable, and natural in English or Chinese.
   - Claims connect to observed or supplied evidence.
   - Product shape, color, quantity, and accessories stay consistent.
   - A+ modules feel like one listing story rather than unrelated ads.

## Copy Rules

- Write English copy for Amazon shopper-facing assets by default.
- Provide Chinese planning notes when the user works in Chinese.
- Keep visible image text short: headline, proof phrase, 2-4 labels, or compact bullets.
- Prefer concrete buyer language over empty phrases like "premium quality" or "perfect experience".
- Do not put internal labels such as `slot_type` or `buyer_question` into final visible copy.

## Revision Routing

- Claim issue: remove, soften, or ask for proof.
- Main image issue: revise product angle, silhouette, crop, lighting, or included items.
- Secondary image issue: revise that image's buyer question and module type.
- A+ flow issue: reorder modules around buyer decision flow.
- Text issue: rewrite visible copy only.
- Product drift: strengthen product reference constraints and regenerate affected assets only.

## Reference

Read `references/module-library.md` when choosing Amazon image slots, A+ module patterns, copy shapes, or audit criteria.
