---
name: photography-scene-design
description: "Professional photography equipment, parameter, and case recipe guide for AI image generation of characters, props, and scenes. Use when converting camera bodies, lens brands, focal lengths, apertures, color temperature, lighting angles, lighting setups, depth of field, bokeh, film looks, or cinema lens aesthetics into prompts for GPT-image-2, nanobanana2, nanobananapro, seedream 5.0, and other text-to-image/image-to-image models."
---

# Photography Scene Design (Character · Props · Scene)

**Purpose**: Inject real photography equipment parameters into AI image generation. By specifying camera bodies, lens brands, focal lengths, and apertures, precisely control image texture, depth of field, perspective, and atmosphere to enhance the professionalism and realism of character/prop/scene designs.

## Use Cases

- Character illustrations, portrait photography, fashion shoots
- Prop detail close-ups, product photography
- Scene atmosphere maps, concept design, environment rendering
- Images requiring specific photography equipment aesthetics (film look, medium format texture, cinema lens style, etc.)

## Core Principles

1. **Equipment Serves the Image**: Choosing equipment parameters is to achieve specific visual effects, not to stack brand names
2. **Parameter Coordination**: Focal length, aperture, camera body, color temperature, and lighting angle must all be reasonably matched — avoid impossible combinations
3. **One Set Per Prompt**: Specify one set of equipment parameters per prompt, don't mix multiple sets
4. **Model Adaptation**: Adapt equipment descriptions as natural language for different image models (GPT-image-2, nanobanana series, seedream 5.0)
5. **Use Case Recipes First**: For concrete generation tasks, check the case index, choose the closest recipe, then replace subject, scene, lighting, color temperature, and style variables
6. **Color Temperature Matches Mood**: Warm color temperatures (2700-3400K) convey intimacy and warmth; cool color temperatures (6500-7500K) convey detachment and chill — choose based on the image's emotional tone
7. **Lighting Angle Shapes Dimension**: Front light is flat and soft, side light is dimensional, backlight is dreamy — the lighting angle determines the subject's volume and atmosphere

---

## I. Camera Body Brand Quick Reference

### Full Frame / Medium Format (Image Quality Priority)

| Brand | Representative Models | Image Characteristics | Suitable Scenes |
|-------|----------------------|----------------------|-----------------|
| Canon | EOS R5 / R6 Mark II | Flattering skin tones, saturated colors, clean shadows | Portraits, fashion, commercial photography |
| Nikon | Z8 / Z9 | True-to-life colors, extreme sharpness, high dynamic range | Landscape, product, documentary |
| Sony | A7R V / A7 IV | High resolving power, precise AF, wide latitude | All-purpose, portraits, street |
| Fujifilm | GFX 100S / X-T5 | Unique film color simulation, medium format texture | Humanitarian, portraiture, film style |
| Leica | M11 / Q3 | German rendering, delicate transitions, unique atmosphere | Street, humanitarian, art photography |
| Hasselblad | X2D 100C | Medium format ultra-high detail, top-tier color science | Fashion, commercial ads, fine products |
| Phase One | IQ4 150MP | 150 megapixels, ultimate detail, precise color | High-end commercial, art reproduction |

### Cinema / Video Bodies (Cinematic Texture)

| Brand | Representative Models | Image Characteristics | Suitable Scenes |
|-------|----------------------|----------------------|-----------------|
| ARRI | ALEXA 35 / Mini LF | Natural skin tones, cinema-grade latitude, soft highlights | Cinematic characters, narrative scenes |
| RED | V-RAPTOR / KOMODO | High resolution, sharp details, tech aesthetic | Sci-fi, action, high-detail scenes |
| Blackmagic | URSA Mini Pro 12K | High dynamic range, Raw color space | Indie films, concept scenes |

### Film Cameras (Vintage Texture)

| Brand | Representative Models | Image Characteristics | Suitable Scenes |
|-------|----------------------|----------------------|-----------------|
| Contax | T2 / G2 | Zeiss lens, warm tones, soft transitions | Vintage portraits, Japanese-style shoots |
| Mamiya | RZ67 / 7II | Medium format film, creamy blur, strong dimensionality | Portraiture, fashion film look |
| Pentax 67 | 6x7 | Large format film, extremely shallow DOF, rich tones | Portraits, landscape, artistic |
| Rolleiflex | 2.8F | Twin-lens reflex, square format, classical charm | Classical portraits, street humanitarian |

---

## II. Lens Brand Quick Reference

### Premium Optical Brands

| Brand | Characteristics | Representative Lenses | Suitable Pairing |
|-------|----------------|----------------------|-----------------|
| Zeiss | Ultimate sharpness, chromatic aberration control, 3D pop | Otus 55/1.4, Milvus 85/1.4 | High-end portraits, products |
| Leica | German rendering, swirly bokeh, delicate transitions | Summilux 50/1.4, Noctilux 75/1.25 | Humanitarian, art, atmosphere |
| Canon L | Red ring designation, skin tone optimization, fast AF | RF 85/1.2L, RF 50/1.2L | Commercial portraits, weddings |
| Nikon S | Nano coating, flare resistance, high resolution | Z 50/1.2S, Z 85/1.2S | All-purpose, high sharpness needs |
| Sony GM | High MTF, ultra-fast AF, lightweight | FE 85/1.4GM II, FE 50/1.2GM | Portraits, sports, street |

### Professional Third-Party / Art Lenses

| Brand | Characteristics | Representative Lenses | Suitable Pairing |
|-------|----------------|----------------------|-----------------|
| Sigma Art | Extreme sharpness, large aperture, value | 35/1.4 Art, 85/1.4 Art | All-purpose sharp imagery |
| Voigtlander | Manual focus, vintage bokeh, compact | Nokton 50/1.2, 40/1.2 | Artistic, street, atmosphere |
| Helios | Swirly bokeh, Soviet lens | Helios 44-2 58/2 | Dreamy swirl, vintage portraits |
| Petzval | Vortex bokeh, sharp center soft edges | Lomography Petzval 85/2.2 | Dramatic portraits, fantasy |
| Cooke | Cinema lens, Cooke Look soft rendering | S7/i 75mm T2.0 | Cinematic texture, narrative scenes |
| ARRI/Zeiss | Master Prime series, cinema-grade | Master Prime 50/T1.3 | Cinema lighting, professional scenes |

---

## III. Focal Length Guide

### Focal Length & Perspective Quick Reference

| Focal Range | Type | Perspective Effect | Character/Scene Application |
|-------------|------|-------------------|---------------------------|
| 14-20mm | Ultra-wide | Strong perspective distortion, extreme spatial exaggeration | Architectural interiors, full environments, oppressive scenes |
| 24-28mm | Wide angle | Moderate perspective, prominent foreground | Environmental portraits, full-body street, scene atmosphere |
| 35mm | Mild wide | Close to human eye, natural without distortion | Documentary, street, environmental portraits |
| 50mm | Standard | Closest to human eye perspective, no distortion | General portraits, everyday scenes, products |
| 85mm | Medium telephoto | Slight compression, best facial proportions | Portrait golden focal length, half-body close-up |
| 105-135mm | Telephoto | Noticeable compression, subject stands out with background blur | Close-up portraits, prop details, emotional rendering |
| 200-400mm | Super telephoto | Extreme compression, foreground-background stacking | Distant figures, spatial compression, dreamy atmosphere |
| 100mm Macro | Macro | 1:1 magnification, ultimate detail | Prop close-ups, jewelry, microscopic world |

### Focal Length Selection Guide

| Design Goal | Recommended Focal Length | Reason |
|-------------|------------------------|--------|
| Full-body character + environment context | 24-35mm | Can accommodate environmental information, establish character-space relationship |
| Half-body / three-quarter | 50-85mm | Natural facial proportions, moderate DOF highlighting subject |
| Facial close-up | 85-135mm | Best facial compression, avoids nose distortion |
| Prop/accessory detail | 90-105mm Macro | Magnified detail, completely blurred background |
| Grand scenes/architecture | 14-24mm | Wide field of view, establishes spatial sense |
| Multi-character group shot | 35-50mm | Natural perspective, multiple people without distortion |

---

## IV. Aperture Guide

### Aperture & Depth of Field Quick Reference

| Aperture | DOF Effect | Image Characteristics | Suitable Scenes |
|----------|-----------|----------------------|-----------------|
| f/1.0-f/1.2 | Extremely shallow DOF | Only eyes sharp, everything else dissolved into creamy bokeh | Ultimate atmosphere portraits, dreamy close-ups |
| f/1.4-f/1.8 | Very shallow DOF | Face sharp, large areas of background blur | Standard portraits, character illustrations, emotional rendering |
| f/2.0-f/2.8 | Shallow DOF | Upper body sharp, soft background separation | Half-body portraits, product photography, prop close-ups |
| f/4.0-f/5.6 | Moderate DOF | Full body sharp, slight background blur | Full-body portraits, fashion, environmental portraits |
| f/8.0-f/11 | Deep DOF | Entire frame clear and sharp | Scene design, architecture, group shots, landscape |
| f/16-f/22 | Very deep DOF | Everything from foreground to infinity is clear | Grand scenes, panoramas, product catalogs |

### Bokeh Styles

| Type | Characteristics | Source |
|------|----------------|--------|
| Creamy bokeh | Smooth transitions without outlining, round orbs | Canon RF 85/1.2L, Sony 85/1.4GM |
| Swirly bokeh | Out-of-focus areas rotate in a vortex pattern | Helios 44-2, Petzval 85 |
| Hard bokeh | Sharp-edged orbs with onion ring patterns | Mirror lenses, some vintage lenses |
| Soft bokeh | Overall hazy, dreamy | Soft-focus lenses, Leica Thambar |
| Starbursts | Point light sources form radiating star patterns | Small apertures f/11-f/16 |

---

## V. Color Temperature Guide

### Color Temperature Quick Reference

| Kelvin | Name | Visual Effect | Suitable Scenes |
|--------|------|---------------|-----------------|
| 2000K | Candle/Firelight | Extreme warm orange-red | Cozy interiors, candlelight, campfire, vintage warm tones |
| 2700-3200K | Tungsten/Warm White | Warm yellow tones | Indoor warm light, bars, vintage scenes, dusk interiors |
| 3400K | Photographic Tungsten | Warm white tones | Studio warm lighting, cinematic interiors |
| 4000-4500K | Fluorescent/Dawn-Dusk | Neutral warm | Office scenes, dawn/dusk transitions, natural interiors |
| 5000-5500K | Daylight/Flash | Standard white | Studio standard, commercial products, neutral skin tones |
| 5600K | Daylight WB | Natural white | Outdoor daylight, standard commercial photography, accurate color |
| 6000-6500K | Cloudy/Shade | Slight cool tone | Overcast outdoor, shaded areas, cool emotional mood |
| 7000-7500K | Shadow/Cold | Cool blue-white tones | Snow scenes, cold moods, sci-fi scenes, polar regions |
| 8000K+ | Extreme Cool | Obvious blue tone | Polar nights, surreal cold tones, cyberpunk |

### Color Temperature Selection Guide

| Design Goal | Recommended Kelvin | Reason |
|-------------|---------------------|--------|
| Warm intimate portrait | 2700-3200K | Warm tones create intimacy, flattering skin shift |
| Natural realistic skin | 5000-5500K | Close to standard daylight, most accurate skin reproduction |
| Cinematic narrative warm | 3200-3400K | Simulates indoor tungsten, cinematic warmth |
| Cold lonely mood | 6500-7500K | Cool tones convey detachment and melancholy |
| Cyberpunk/Sci-fi | 4000K mixed with 7000K+ | Warm-cool mixed sources create tech contrast |
| Snow/Polar cold tone | 7000-7500K | Reinforces environmental cold, white detail stays clear |
| Golden hour outdoor | 3200-4000K | Simulates sunset low-color-temperature warm light |
| Commercial product accuracy | 5000-5500K | Neutral color temperature ensures no color shift |

### Color Temperature & White Balance Coordination

- **Match source color temperature**: Set white balance to match the ambient light source for accurate color reproduction
- **Intentional warm shift**: Set white balance above actual source temperature (e.g., 6500K in daylight) for overall warm image
- **Intentional cool shift**: Set white balance below actual source temperature (e.g., 3200K under tungsten) for overall cool image
- **Mixed sources**: When warm and cool sources coexist (e.g., indoor tungsten + outdoor daylight), emphasize one side while preserving the other's color difference for layered depth

---

## VI. Lighting Angle Guide

### Lighting Angle Quick Reference

| Angle | Name | Visual Effect | Suitable Scenes |
|-------|------|---------------|-----------------|
| 0° Front | Front Light | Even illumination, minimal shadow | Beauty close-ups, ID photos, fresh high-key portraits |
| 15-30° | Butterfly/Paramount | Butterfly shadow under nose, cheekbone highlight | Fashion female portraits, glamour style, vintage Hollywood |
| 30-45° | Rembrandt | Inverted triangle on cheek, strong dimensionality | Dramatic portraits, cinematic feel, painterly quality |
| 45-60° | Loop Lighting | Short unconnected nose shadow, natural depth | General commercial portraits, natural feel, wedding |
| 90° Side | Split/Side Light | Face split half light half dark | Masculine portraits, low-key mood, product texture |
| 120-135° | Rim/Back-Side | Edge contour light, front slightly dark | Hair light, subject-background separation, atmospheric portrait |
| 180° Back | Backlight | Subject edge halo, front needs fill | Silhouettes, dreamy halo, translucent materials, backlit portraits |
| Top | Top Light | Deep eye sockets, heavy downward shadows | Noon outdoor, stage overhead, dramatic oppression |
| Under | Under Light | Unnatural, horror feel | Horror themes, dramatic effects, special lighting |

### Lighting Angle Selection Guide

| Design Goal | Recommended Angle | Reason |
|-------------|-------------------|--------|
| Flawless beauty | 0° front light + large softbox | Even illumination removes blemishes, clean skin |
| Fashion glamour portrait | 15-30° butterfly light | Cheekbone highlight adds dimension, elegant nose shadow |
| Cinematic narrative depth | 30-45° Rembrandt light | Face triangle creates dramatic depth |
| Natural general commercial | 45-60° loop light | Dimensional but not extreme, broadly applicable |
| Masculine/antihero | 90° side light | Light-dark split intensifies bone structure and texture |
| Hair contour separation | 120-135° rim light | Contour light separates subject from background |
| Dreamy backlight atmosphere | 180° backlight | Halo, translucent feel, romantic mood |
| Product material texture | 45-90° side/rim light | Raking light reveals surface relief and detail |

### Lighting Setup Quick Reference

| Setup | Components | Suitable Scenes |
|-------|------------|-----------------|
| Three-point lighting | Key + Fill + Rim | General commercial, portraits, products |
| Rembrandt setup | 45° key + weak fill | Dramatic portraits, cinematic feel |
| Butterfly setup | High front key + bottom reflector | Fashion, glamour, beauty |
| Split setup | 90° single-side key | Masculine portraits, low-key mood |
| Clamshell | Top key + bottom reflector | Beauty, skincare, soft flawless |
| Low-key single source | Single light, no fill | Low-key portraits, black-background products |

---

## VII. Prompt Template Library

### Character Design — Portrait Close-up
```
Shot on Canon EOS R5 with RF 85mm f/1.2L USM at f/1.4, 3200K warm color temperature, 45° loop lighting, a young woman with silver hair gazes into the lens, soft window light illuminating her face, extremely shallow depth of field with creamy bokeh dissolving the background into warm golden tones, skin texture and iris details rendered with exceptional clarity.
```

### Character Design — Full Body Illustration
```
Captured with Sony A7R V and Sigma 35mm f/1.4 Art at f/2.8, mixed 4000K/7000K neon color temperature, 135° side-back rim lighting, a cyberpunk warrior stands in a rain-soaked neon alley, full body visible from head to boots, ambient neon reflections on wet surfaces, medium depth of field keeping the character sharp while the background glows with colorful bokeh.
```

### Character Design — Cinematic Portrait
```
Filmed on ARRI ALEXA 35 with Cooke S7/i 75mm T2.0, 3200K warm practical color temperature, 120° Rembrandt lighting, cinematic portrait of a detective in a dimly lit office, warm practical lighting from a desk lamp, the Cooke Look rendering skin with gentle halation and smooth tonal transitions, shallow depth of field isolating the subject from the noir background.
```

### Prop Design — Detail Close-up
```
Shot on Hasselblad X2D 100C with Zeiss Otus 100mm Macro at f/4, 5500K studio color temperature, 120° rim lighting, extreme close-up of an ornate mechanical pocket watch, every gear tooth and engraving rendered in extraordinary detail, dark velvet background completely dissolved into pure black, studio rim lighting accentuating metallic textures.
```

### Scene Design — Grand Environment
```
Captured with Nikon Z8 and Nikkor Z 14-24mm f/2.8S at 16mm f/8, 4000K twilight color temperature, 15° low-angle sunlight, a vast cyberpunk cityscape at twilight, towering megastructures receding into atmospheric haze, deep depth of field rendering every architectural detail from foreground market stalls to distant skyscrapers, dramatic perspective lines converging at the horizon.
```

### Scene Design — Atmospheric Interior
```
Shot on Fujifilm GFX 100S with GF 80mm f/1.7 at f/2.0, 3400K warm golden-hour color temperature, 45° side window light, a quiet Japanese tea room in late afternoon, golden hour light streaming through shoji screens, medium format rendering delivering exceptional tonal gradation and three-dimensionality, gentle bokeh on background elements.
```

### Vintage Film — Character Shoot
```
Shot on Contax T2 with Zeiss Sonnar 38mm f/2.8, 4000K warm daylight color temperature, 60° natural available light, Kodak Portra 400 film, a woman in a summer dress walking through a sunlit garden, characteristic warm color palette with soft highlight rolloff, natural film grain adding organic texture, the timeless Contax rendering style.
```

### Product/Props — Commercial Grade
```
Photographed with Phase One IQ4 150MP and Schneider 120mm LS f/4 Macro, 5500K studio standard color temperature, 90° side lighting, a luxury perfume bottle on reflective black acrylic surface, 150 megapixel resolution capturing every crystal facet and light refraction, controlled studio lighting with precise specular highlights, absolute color accuracy.
```

---

## VIII. Quick Intent Matching Guide

| Design Intent | Recommended Equipment Combo | Recommended Color Temp | Recommended Light Angle |
|---------------|---------------------------|----------------------|------------------------|
| Dreamy portrait / atmosphere | Canon R5 + RF 85/1.2L @ f/1.2 | 3200K warm | 180° backlight or 45° loop |
| Sharp character illustration | Sony A7RV + 85GM II @ f/1.8 | 5500K standard | 45° loop light |
| Cinematic narrative feel | ARRI ALEXA 35 + Cooke 75mm T2.0 | 3200K warm | 30-45° Rembrandt |
| Vintage film look | Contax T2 / Mamiya RZ67 + Portra 400 | 4000K warm white | 60° natural light |
| Prop macro detail | Hasselblad X2D + Zeiss 100mm Macro | 5500K standard | 120° rim light |
| Grand scene | Nikon Z8 + 14-24/2.8S @ f/8 | 4000K twilight | 15° low-angle sun |
| German rendering humanitarian | Leica M11 + Summilux 50/1.4 | 5000K daylight | 45-60° natural side |
| Japanese fresh style | Fujifilm X-T5 + 56/1.2 (Classic Chrome) | 5500K daylight | 45° window light |
| Sci-fi / high-tech | RED V-RAPTOR + Sigma 35 Art | 4000K/7000K mixed | 90° top + side |
| Fantasy / dramatic | Petzval 85/2.2 (vortex bokeh) | 3200K warm | 180° stage backlight |

---

## IX. Image Model Integration

Incorporate equipment parameters when generating prompts:

1. **GPT-image-2**: Describe equipment and parameters directly in natural language within the prompt
   - Example: `Photo taken with a Canon EOS R5, 85mm f/1.2 lens, shallow depth of field, creamy bokeh background`

2. **nanobanana2 / nanobananapro**: Incorporate equipment info as part of the image quality description
   - Example: `shot on Hasselblad medium format, 80mm lens at f/2, cinematic lighting, ultra-detailed skin texture`

3. **seedream 5.0**: Supports rich photography style descriptions, combining equipment + color temperature + lighting angle + depth of field as comprehensive style guidance
   - Example: `professional photography, Canon EOS R5, 85mm f/1.2L lens, f/1.4 aperture, 3200K warm color temperature, 45° loop lighting, natural window light, extremely shallow depth of field, creamy bokeh, warm golden tones, high detail skin texture`

4. **Universal format**: `[Equipment info] + [Color temperature] + [Lighting angle] + [Subject description] + [Lighting environment] + [DOF/bokeh description]`

### Notes

- Equipment parameters serve as quality cues — models don't truly simulate optical physics, but can guide style direction
- This skill can be combined with a "Cinema Lens Language" skill: this one controls static image quality, while that one controls dynamic camera movement
- Aperture and focal length pairings should be realistic: ultra-wide f/1.2 lenses barely exist in reality
- seedream 5.0 responds well to photography style keywords — consider adding `professional photography` or `cinematic still` at the beginning of prompts for enhanced results
- In case recipes, subjects, professions, materials, and scenes are replaceable; preserve the relationship between equipment, focal length, aperture, and intended image result

---

## References and Case Library

The quick reference tables above provide rapid equipment selection. For **detailed parameter descriptions** and **ready-to-use complete prompt templates** for each equipment combination, please refer to:

👉 [Full Photography Equipment Reference Manual](./references/full_photography_guide.md)

When matching a concrete intent to a reusable recipe, start with:

👉 [Structured Case Index](./references/case_index.md)

Usage:
1. Select equipment from the quick tables or case index based on design intent
2. Open the relevant case file and read applicability, image result, replaceable variables, and avoid notes
3. Fine-tune based on the specific character, prop, or scene requirements and incorporate into the generation prompt
