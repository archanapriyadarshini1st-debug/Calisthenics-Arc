# Exercise Catalogue — Research Notes and Coverage Audit

**Research snapshot:** 9 November 2026  
**Repository:** [Calisthenics-Arc](https://github.com/archanapriyadarshini1st-debug/Calisthenics-Arc)  
**Catalogue:** [exercise-catalogue.md](./exercise-catalogue.md)  
**Result:** 277 catalogue rows across 13 movement sections; 277 distinct names after simple exact-name cleanup.

## Important completeness statement

This is a broad, cross-checked working catalogue, **not** a provably exhaustive list of every calisthenics exercise or every website. There is no authoritative global registry of exercise names. Websites differ in scope, use different aliases, count progression stages differently, include weighted/machine exercises in bodyweight filters, and often hide entries behind search or pagination. Search engines also do not expose every page, and some sites restrict crawling.

I cannot honestly certify that no site was missed or that every movement in existence has been found. The “10-pass” audit below checks coverage and quality from ten angles; it does not mean ten complete crawls of the entire internet.

## Source strategy

The catalogue was built by comparing fundamental movement-pattern frameworks, public exercise libraries, university exercise resources, and pediatric training-safety guidance. The source list below is intentionally weighted toward foundational, controlled movements and safety principles rather than advanced-skill tutorials.

### Sources consulted

1. **American Academy of Pediatrics (AAP), “Resistance Training for Children and Adolescents.”** Clinical report reaffirmed November 2024. It recognizes bodyweight movements as a form of resistance training and emphasizes proper technique and qualified supervision for youth.  
   https://publications.aap.org/pediatrics/article/145/6/e20201011/76942/Resistance-Training-for-Children-and-Adolescents

2. **American Council on Exercise (ACE), Exercise Library.** Used as a broad reference for body-part groupings and equipment/no-equipment movement examples.  
   https://www.acefitness.org/resources/everyone/exercise-library/

3. **NHS, Strength Exercises.** Used for ordinary home-based strength movement examples and stable-chair / gradual-build-up safety context.  
   https://www.nhs.uk/live-well/exercise/strength-exercises/

4. **Keele University, Active Keele Exercise Library.** Used as a university sports-service cross-check for lower-body, hip, hamstring, mobility, and conditioning movement names.  
   https://www.keele.ac.uk/sportatkeele/activekeele/exerciselibrary/

5. **Calisthenics Association, “Building Foundational Movement Patterns.”** Used to cross-check squat, hinge, horizontal/vertical push and pull, and trunk-stability categories.  
   https://calisthenicsassociation.org/lessons/building-foundational-movement-patterns

6. **Calisthenics Association, “Prehab Exercises for Calisthenics.”** Used as a secondary cross-check for scapular control, shoulder preparation, and basic stability movements.  
   https://calisthenicsassociation.org/lessons/prehab-exercises

7. **Bodyweight Library, “FAQ & Guide.”** Used to compare a broader movement taxonomy covering squat, lunge, hinge, push, pull, core, locomotion, carry, and rotation.  
   https://bodyweightlibrary.com/en/faq

The source set is a representative sample, not a list of every website consulted or every website that exists. Large searchable directories were compared at the category/name level where search results exposed them. Their raw totals were not copied as a claim of unique exercises because some mix in external-load movements, machine exercises, alternate labels, or multiple progression stages.

## Ten-pass coverage and quality audit

| Pass | What was checked | Outcome |
|---|---|---|
| 1. Movement-pattern coverage | Push, pull, squat, lunge, hinge, core, locomotion, balance, and mobility | All represented |
| 2. Upper-body push coverage | Horizontal push, shoulder-emphasis push, triceps, and scapular-control names | Represented; equipment-dependent support work tagged |
| 3. Upper-body pull coverage | Vertical pulls, horizontal rows, hangs, and common grip variants | Represented; bar/ring dependencies tagged |
| 4. Lower-body coverage | Squat, unilateral/lunge, step, hip hinge, glute, hamstring, calf, and foot patterns | All represented |
| 5. Trunk coverage | Flexion, rotation, anti-extension, lateral stability, and controlled bracing | Represented |
| 6. Movement-type coverage | Dynamic reps, isometric holds, locomotion, balance, and mobility | All represented |
| 7. Equipment audit | Floor, wall, stable step/chair, fixed bar, parallel bars, rings, and sliders | Tags added; unavailable/optional equipment called out |
| 8. Alias and duplication audit | Common duplicate labels and small variation differences | Canonical names used where practical; aliases grouped |
| 9. Safety-screening audit | High-risk acrobatics, extreme leverage, maximal finger/one-arm loading, kipping/explosive stunts, and improvised anchors | Excluded from this youth-facing catalogue; no how-to or progression instructions provided |
| 10. Repository and source audit | Existing project files, materials notes, source links, and claim wording | Existing workout logs and skill history left untouched; completeness limits stated |

## Known limits and next-review items

- **Not an internet-wide crawl:** public search indexing is incomplete; private apps, dynamically loaded libraries, paywalled databases, regional terminology, and unindexed pages may contain additional names.
- **Not a clinical or rehab database:** this catalogue is for general movement indexing. Rehabilitation exercises need individualized professional guidance.
- **Not all weighted calisthenics:** weighted vest, dip-belt, backpack, dumbbell, barbell, cable, and machine variants are outside the bodyweight-only scope.
- **Not every skill family:** high-risk advanced gymnastics/acrobatic work is intentionally excluded, even when a general exercise site lists it.
- **Not all possible permutations:** grip widths, angles, tempos, pauses, ranges, and assistances can produce effectively unlimited variants.
- **Equipment status can change:** check `materials.md` before the mentor recommends a bar-, ring-, or parallel-bar-dependent exercise.

## Reproducible update procedure

When updating this catalogue, search by movement family rather than by the phrase “all exercises.” Compare each candidate with the canonical names, note the source and date, verify whether it is truly bodyweight, assign equipment tags, and run the same ten checks. Do not inflate the total by counting aliases or trivial grip changes as brand-new movements.
