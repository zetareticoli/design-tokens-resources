## 1. Audit Preparation

-  [ ] Define audit scope (which areas/components to analyze)
-  [ ] Prepare documentation tools (spreadsheet, analysis tools)
-  [ ] Involve stakeholders (designer, developer, product)
-  [ ] Establish reference metrics

## 2. Figma Analysis

-  [ ] Export all local styles (colors, typography, effects)
-  [ ] Identify hardcoded values in layers
-  [ ] Verify use of native Figma variables
-  [ ] Check if token plugins exist (Tokens Studio, Figma Tokens)
-  [ ] Document current naming conventions
-  [ ] Identify duplications (e.g.: #333, #323232, rgb(51,51,51))
-  [ ] Catalog components and variants

## 3. CSS/SASS/LESS Analysis

-  [ ] Use CSS Stats for automated analysis
-  [ ] Extract all CSS custom properties variables (--var)
-  [ ] Catalog SASS/LESS variables
-  [ ] Identify hardcoded values in code
-  [ ] Analyze computed styles with Chrome DevTools
-  [ ] Quantify duplications (e.g.: 47 shades of gray vs 8 needed)
-  [ ] Verify naming inconsistencies (e.g.: button-primary, btn-main, primary-button)

## 4. JSON File Analysis

-  [ ] Verify presence of existing token configuration files
-  [ ] Validate JSON structure against standards (W3C DTCG)
-  [ ] Check hierarchical organization
-  [ ] Verify presence of metadata (descriptions, categories)
-  [ ] Identify deprecated or unused tokens
-  [ ] Check consistency across different files (theme, component, core)

## 5. Cross-Platform Analysis

-  [ ] Compare values between Figma and code
-  [ ] Verify discrepancies between design and implementation
-  [ ] Document current source of truth
-  [ ] Identify target platforms (web, iOS, Android)

## 6. Categorization

-  [ ] Colors (brand, semantic, functional)
-  [ ] Typography (font families, sizes, weights, line-heights)
-  [ ] Spacing (margin, padding, gap)
-  [ ] Grid (breakpoints, layout, container)
-  [ ] Effects (shadows, blur, opacity)
-  [ ] Animations (duration, easing)
-  [ ] Borders (radius, width, style)

## 7. Issue Documentation

-  [ ] Quantify unique values vs needed (e.g.: "200 unique colors")
-  [ ] Identify missing patterns (e.g.: spacing 8px, 10px, 12px without logic)
-  [ ] Document naming inconsistencies
-  [ ] Highlight lack of semantic tokens
-  [ ] Report accessibility issues (contrast, text sizes)

## 8. Output and Reporting

-  [ ] Create complete inventory in spreadsheet
-  [ ] Generate report with key metrics
-  [ ] Prepare visual examples of inconsistencies
-  [ ] Define gap analysis (what's missing, what's redundant)
-  [ ] Propose migration priorities

## 9. Validation

-  [ ] Review with design team
-  [ ] Review with development team
-  [ ] Identify quick wins vs complex refactoring
-  [ ] Estimate effort by category
