# Fitness Program Generation Prompts

This document contains structured prompt templates for generating personalized fitness programs based on different training goals. Use these templates with AI models or as guidelines for manual program creation.

---

## Client Data Placeholders

Use these placeholders throughout all prompts:
- `{{clientName}}` - Client's full name
- `{{age}}` - Client's age
- `{{gender}}` - Client's gender
- `{{fitnessLevel}}` - Beginner / Intermediate / Advanced
- `{{primaryGoal}}` - Main fitness objective
- `{{secondaryGoal}}` - Secondary fitness objective (optional)
- `{{trainingDays}}` - Number of days per week available
- `{{sessionDuration}}` - Minutes per session
- `{{equipment}}` - Available equipment
- `{{limitations}}` - Injuries or physical limitations
- `{{experience}}` - Years of training experience
- `{{preferences}}` - Training style preferences

---

## 1. Strength Training Prompt Template

### Primary Use Case
Building maximal strength, powerlifting, or developing raw force production.

### Prompt Template

```
Create a comprehensive strength training program for {{clientName}}, a {{age}}-year-old {{gender}} with {{fitnessLevel}} experience level.

CLIENT PROFILE:
- Primary Goal: {{primaryGoal}} (Strength Development)
- Training Frequency: {{trainingDays}} days per week
- Session Duration: {{sessionDuration}} minutes
- Available Equipment: {{equipment}}
- Limitations/Injuries: {{limitations}}
- Training Experience: {{experience}} years

PROGRAM REQUIREMENTS:
1. Focus on compound movements (squat, bench press, deadlift, overhead press)
2. Progressive overload scheme with specific percentages of 1RM
3. Low rep ranges (1-6 reps) for main lifts
4. Adequate rest periods (3-5 minutes between heavy sets)
5. Periodization model (linear, undulating, or block periodization)
6. Accessory work to support main lifts and address weaknesses
7. Deload weeks every 4-6 weeks to prevent overtraining

DELIVERY FORMAT:
- 12-week program broken into 3-4 week blocks
- Detailed exercise selection with sets, reps, and intensity (%1RM or RPE)
- Progression scheme (how to increase load weekly)
- Technical cues for each main lift
- Warm-up protocols specific to strength training
- Recovery recommendations

ADDITIONAL CONSIDERATIONS:
- Include mobility work for improved lifting mechanics
- Address muscle imbalances that could limit strength gains
- Provide guidelines for testing 1RM safely
- Include mental preparation strategies for heavy lifts
```

### Nutrition Integration
If using Biorhythm Nutrition protocol, add:
```
NUTRITION PROTOCOL:
Integrate the Biorhythm Nutrition approach with emphasis on:
- High protein intake (2.0-2.4g per kg body weight) for strength adaptation
- Carbohydrate timing around heavy training sessions
- Adequate caloric surplus for strength gains (200-300 calorie surplus)
- Strategic meal timing to support recovery between sessions
```

---

## 2. Hypertrophy Prompt Template

### Primary Use Case
Muscle building, bodybuilding, aesthetic development, or increasing muscle mass.

### Prompt Template

```
Design a hypertrophy-focused training program for {{clientName}}, a {{age}}-year-old {{gender}} at {{fitnessLevel}} level.

CLIENT PROFILE:
- Primary Goal: {{primaryGoal}} (Muscle Hypertrophy)
- Training Frequency: {{trainingDays}} days per week
- Session Duration: {{sessionDuration}} minutes
- Available Equipment: {{equipment}}
- Limitations/Injuries: {{limitations}}
- Training Experience: {{experience}} years
- Aesthetic Focus: {{preferences}}

PROGRAM REQUIREMENTS:
1. Volume-based approach (10-20 sets per muscle group per week)
2. Rep ranges optimized for hypertrophy (6-12 reps primary, 12-20 reps accessory)
3. Muscle group split appropriate for training frequency
4. Exercise variety to target muscles from multiple angles
5. Time under tension protocols where applicable
6. Progressive overload through volume, intensity, or density
7. Moderate rest periods (60-90 seconds)

DELIVERY FORMAT:
- 8-12 week program with mesocycle structure
- Detailed exercise selection with tempo prescriptions (e.g., 3-1-2-0)
- Set and rep schemes with progression model
- Muscle group breakdown showing weekly volume distribution
- Mind-muscle connection cues for key exercises
- Techniques: drop sets, supersets, rest-pause (where appropriate)
- Deload protocol

BODYPART FOCUS:
- Specify training split (Push/Pull/Legs, Upper/Lower, Bro Split, etc.)
- Address lagging muscle groups based on client assessment
- Include weak point specialization phases if needed
- Balance between compound and isolation exercises

RECOVERY PROTOCOLS:
- Stretching routines for trained muscle groups
- Active recovery recommendations
- Sleep optimization for muscle growth
- Stress management techniques
```

### Nutrition Integration
```
NUTRITION PROTOCOL:
Apply Biorhythm Nutrition principles for hypertrophy:
- Protein intake: 1.8-2.2g per kg body weight distributed across 4-5 meals
- Caloric surplus: 300-500 calories above maintenance
- Carbohydrate cycling based on training volume
- Intra-workout nutrition for sessions over 60 minutes
- Post-workout anabolic window optimization
- Micronutrient focus for recovery and hormonal health
```

---

## 3. Endurance Training Prompt Template

### Primary Use Case
Cardiovascular fitness, marathon/race training, stamina development, or aerobic capacity.

### Prompt Template

```
Develop a comprehensive endurance training program for {{clientName}}, a {{age}}-year-old {{gender}} with {{fitnessLevel}} conditioning level.

CLIENT PROFILE:
- Primary Goal: {{primaryGoal}} (Endurance Development)
- Training Frequency: {{trainingDays}} days per week
- Session Duration: {{sessionDuration}} minutes
- Available Equipment: {{equipment}}
- Event Goal (if applicable): {{eventDetails}}
- Limitations/Injuries: {{limitations}}
- Current Fitness Markers: {{baselineFitness}}

PROGRAM REQUIREMENTS:
1. Aerobic base building with zone-based training
2. Progressive volume increase (following 10% rule)
3. Mix of steady-state and interval training
4. Heart rate zone prescriptions (Zone 2, Zone 3, Zone 4, Zone 5)
5. Long slow distance (LSD) sessions
6. Tempo runs/rides/swims
7. High-intensity interval training (HIIT) sessions
8. Recovery weeks every 3-4 weeks

DELIVERY FORMAT:
- 12-16 week periodized program
- Weekly training schedule with specific sessions
- Heart rate zones or pace targets for each workout
- Duration and intensity for each session
- Cross-training recommendations to prevent overuse injuries
- Taper protocol if training for specific event
- Benchmark testing schedule (every 4 weeks)

WORKOUT TYPES TO INCLUDE:
- Base aerobic sessions (Zone 2, conversational pace)
- Tempo intervals (Zone 3-4, sustainable hard effort)
- VO2max intervals (Zone 5, maximal efforts)
- Recovery sessions (Zone 1-2, active recovery)
- Long endurance sessions (progressive distance increase)
- Brick workouts (if applicable for multi-sport athletes)

SUPPORTING ELEMENTS:
- Strength training to prevent injuries (1-2x per week)
- Mobility and flexibility work
- Breathing technique optimization
- Pacing strategy development
- Mental endurance training
```

### Nutrition Integration
```
NUTRITION PROTOCOL:
Endurance-specific Biorhythm Nutrition approach:
- Carbohydrate periodization: high carb on hard training days
- Protein: 1.4-1.8g per kg for recovery and muscle preservation
- Hydration strategy: electrolyte timing and amounts
- Fueling during long sessions (30-60g carbs per hour for 90+ min sessions)
- Glycogen loading protocols for events
- Fat adaptation strategies for ultra-endurance goals
- Recovery nutrition timing within 30 minutes post-workout
```

---

## 4. Hybrid Training Prompt Template

### Primary Use Case
Combining multiple fitness qualities (e.g., strength + endurance, or muscle + conditioning).

### Prompt Template

```
Create a hybrid training program for {{clientName}}, a {{age}}-year-old {{gender}} at {{fitnessLevel}} level, focusing on multiple training adaptations.

CLIENT PROFILE:
- Primary Goal: {{primaryGoal}}
- Secondary Goal: {{secondaryGoal}}
- Training Frequency: {{trainingDays}} days per week
- Session Duration: {{sessionDuration}} minutes
- Available Equipment: {{equipment}}
- Limitations/Injuries: {{limitations}}
- Training Experience: {{experience}} years
- Goal Priority: {{goalPriority}} (e.g., 70% strength / 30% endurance)

PROGRAM REQUIREMENTS:
1. Concurrent training approach that minimizes interference effect
2. Strategic session sequencing (strength before cardio when possible)
3. Appropriate volume distribution between competing adaptations
4. Undulating periodization to emphasize different qualities
5. Recovery management critical for multi-modal training
6. Programming to prevent overtraining syndrome

DELIVERY FORMAT:
- 8-12 week program with clear phase objectives
- Daily session structure showing both training modalities
- Intensity and volume management to prevent interference
- Deload weeks every 3-4 weeks
- Monthly assessment of both training qualities
- Adjustment protocols based on client response

HYBRID PROGRAMMING STRATEGIES:
A. Strength + Conditioning
   - Heavy strength work (85%+ 1RM) followed by low-intensity steady-state cardio
   - Separate strength and high-intensity cardio sessions by 6+ hours
   - 3x strength, 2-3x conditioning per week
   - Prioritize strength on fresh days

B. Muscle Building + Athletic Performance
   - Hypertrophy blocks (4 weeks) alternating with power/speed blocks (2-3 weeks)
   - Compound lifts for strength, plyometrics for power, sprints for speed
   - Volume management to allow concurrent adaptations
   - Strategic loading to peak different qualities

C. Endurance + Strength Maintenance
   - 3-4x endurance sessions (primary focus)
   - 2x full-body strength sessions (maintenance volume)
   - Strength sessions on moderate endurance days
   - Avoid heavy lifting before long endurance sessions

D. Fat Loss + Muscle Preservation
   - Resistance training 3-4x per week (to preserve muscle)
   - 2-3x metabolic conditioning sessions
   - Caloric deficit with high protein
   - Training volume moderated for recovery in deficit

PERIODIZATION MODEL:
- Block Periodization: Emphasize one quality per block (4-6 weeks each)
- Concurrent Training: Develop both qualities simultaneously with careful management
- Undulating Priority: Vary emphasis weekly (Week 1-2: Strength focus, Week 3: Endurance focus, repeat)

RECOVERY OPTIMIZATION:
- Sleep target: 8+ hours for hybrid training demands
- Active recovery sessions on off days
- Nutrition timing critical for dual adaptations
- Monitor for signs of overtraining (HRV tracking recommended)
```

### Nutrition Integration for Hybrid Goals
```
NUTRITION PROTOCOL:
Advanced Biorhythm Nutrition for hybrid training:
- Protein: 2.0-2.2g per kg body weight (support both adaptations)
- Carbohydrate cycling: High on strength+conditioning days, moderate on strength-only days
- Caloric targets adjusted based on primary goal priority
- Intra-workout nutrition on hybrid training days (strength + conditioning same session)
- Nutrient timing: Fast-acting carbs/protein immediately post-session
- Supplementation: Creatine for strength, beta-alanine for endurance, BCAAs for recovery
```

---

## 5. Combining Multiple Protocols

### When Client Has Primary AND Secondary Goals

Use this decision tree to structure hybrid programs:

#### STEP 1: Identify Goal Priority Ratio
```
Primary Goal Emphasis: 70-80% of training volume
Secondary Goal Emphasis: 20-30% of training volume

Example:
- Primary: Muscle Building (70%)
- Secondary: Cardiovascular Health (30%)
→ Result: 4 days hypertrophy training, 2 days moderate cardio
```

#### STEP 2: Sequence Training Sessions
```
SAME-DAY TRAINING:
Rule: Perform priority goal first when fresh

Strength + Cardio:
→ Lift weights first, then cardio
→ Minimizes interference effect

Hypertrophy + Conditioning:
→ Resistance training first, metabolic work after
→ Preserves muscle-building stimulus

SEPARATE-DAY TRAINING:
Rule: Allow 24-48 hours between competing stimuli when possible

Monday: Heavy Strength Lower Body
Tuesday: Upper Body Hypertrophy
Wednesday: Endurance/Conditioning
Thursday: Heavy Strength Upper Body
Friday: Lower Body Hypertrophy
Saturday: Active Recovery or Light Conditioning
Sunday: Rest
```

#### STEP 3: Block Periodization for Conflicting Goals
```
When goals directly conflict (e.g., maximal strength + marathon training):

BLOCK 1 (4-6 weeks): Emphasize Primary Goal (80-90%)
- Maintain secondary goal with minimal effective dose

BLOCK 2 (4-6 weeks): Emphasize Secondary Goal (70-80%)
- Continue primary goal at reduced volume

BLOCK 3 (4-6 weeks): Integration Block
- Combine both at moderate volumes
- Peak or test performance in both domains

Example Block Structure:
Weeks 1-6: Strength Focus (4x heavy lifting, 1x light cardio)
Weeks 7-12: Endurance Focus (4x running, 2x strength maintenance)
Weeks 13-16: Integration (3x lifting, 3x running, balanced intensity)
```

#### STEP 4: Nutrition Periodization for Hybrid Goals
```
MATCH NUTRITION TO TRAINING EMPHASIS:

Strength Emphasis Days:
- Higher protein (2.2-2.4g/kg)
- Moderate carbs (4-5g/kg)
- Moderate caloric surplus or maintenance

Endurance Emphasis Days:
- Moderate protein (1.6-1.8g/kg)
- Higher carbs (6-8g/kg)
- Maintenance or slight surplus calories

Hybrid Training Days:
- High protein (2.0-2.2g/kg)
- High carbs (5-7g/kg)
- Caloric surplus to support recovery from both stimuli

Rest Days:
- Maintenance protein (1.8g/kg)
- Lower carbs (3-4g/kg)
- Slight deficit to balance weekly average
```

#### STEP 5: Recovery Protocols for Multi-Goal Programs
```
MANDATORY ELEMENTS:
1. Sleep: 8-9 hours minimum (hybrid training increases recovery demands)
2. Deload Weeks: Every 3-4 weeks, reduce volume by 40-50%
3. Active Recovery: 1-2 days per week of light movement
4. Monitoring: Track HRV, sleep quality, mood, performance metrics

WARNING SIGNS OF OVERTRAINING:
- Decreased performance in both training modalities
- Persistent fatigue despite adequate sleep
- Loss of motivation
- Increased resting heart rate
- Poor sleep quality
- Frequent illness

ACTION: If warning signs appear, implement immediate deload week or take 3-5 full rest days
```

---

## 6. NBA Power Protocol Integration

### When to Apply NBA Power Protocol
Use this protocol for clients focused on explosive power, athletic performance, or sport-specific training.

### Integration Template
```
For {{clientName}} requiring power development:

PHASE 1 - Strength Foundation (Weeks 1-4):
- Build maximal strength using the Strength Training template
- Focus: Compound lifts at 80-90% 1RM for 3-5 reps
- Minimal plyometrics (intro only)

PHASE 2 - Strength-Speed (Weeks 5-8):
- Moderate loads (60-75% 1RM) moved explosively
- Introduce Olympic lift variations (power clean, hang snatch)
- Add basic plyometrics (box jumps, broad jumps)

PHASE 3 - Speed-Strength (Weeks 9-12):
- NBA Power Protocol emphasis
- Light loads (30-50% 1RM) with maximum velocity
- Advanced plyometrics (depth jumps, reactive work)
- Medicine ball throws for rotational power
- Sprint training and acceleration work

EXERCISES FROM NBA POWER PROTOCOL:
- Trap bar jump squats: 3-5 sets x 3-5 reps at 30-40% 1RM
- Hang power cleans: 4-6 sets x 2-3 reps at 60-70% 1RM
- Depth jumps: 3-4 sets x 4-6 reps (box height 30-60cm)
- Med ball chest pass: 3 sets x 8 explosive reps
- Broad jumps: 4 sets x 3 reps for max distance
- Box jumps: 3-4 sets x 3-5 reps (focus on reactive landing)

NUTRITION FOR POWER:
- Creatine monohydrate: 5g daily
- Adequate carbs for explosive training: 5-6g/kg body weight
- Protein for recovery: 2.0g/kg body weight
- Hydration crucial for power output
```

---

## 7. Biorhythm Nutrition Protocol Integration

### Application Across All Goals
The Biorhythm Nutrition protocol should be customized based on training goal:

### General Framework
```
BIORHYTHM NUTRITION CORE PRINCIPLES:

1. CIRCADIAN RHYTHM ALIGNMENT:
   - Larger meals earlier in the day (breakfast and lunch)
   - Training preferably in morning or early afternoon when cortisol is naturally elevated
   - Lighter dinner to support sleep quality
   - 12-hour eating window (e.g., 7am-7pm)

2. TRAINING-DAY NUTRITION:
   Pre-Training (2-3 hours before):
   - Moderate protein + complex carbs
   - Example: Oatmeal with protein powder and berries

   Intra-Training (for sessions 90+ minutes):
   - Fast-acting carbs: 30-60g per hour
   - Electrolytes

   Post-Training (within 30-60 minutes):
   - High protein + simple carbs
   - Example: Protein shake with banana and honey

   Evening (4-6 hours post-training):
   - Balanced meal with vegetables
   - Moderate carbs to replenish glycogen
   - Healthy fats for hormone production

3. REST-DAY NUTRITION:
   - Maintenance calories or slight deficit
   - Higher fat, moderate protein, lower carbs
   - Focus on nutrient-dense whole foods
   - Support recovery and adaptation

4. MACRONUTRIENT TARGETS BY GOAL:

   Strength Training:
   - Protein: 2.0-2.4g/kg
   - Carbs: 4-6g/kg
   - Fats: 1.0g/kg
   - Calories: Maintenance + 200-300

   Hypertrophy:
   - Protein: 1.8-2.2g/kg
   - Carbs: 4-7g/kg
   - Fats: 0.8-1.0g/kg
   - Calories: Maintenance + 300-500

   Endurance:
   - Protein: 1.4-1.8g/kg
   - Carbs: 6-10g/kg (periodized)
   - Fats: 1.0-1.2g/kg
   - Calories: Maintenance + 300-800 (based on volume)

   Fat Loss:
   - Protein: 2.0-2.6g/kg (muscle preservation)
   - Carbs: 2-4g/kg (training days higher)
   - Fats: 0.6-0.8g/kg
   - Calories: Maintenance - 300-500

5. SUPPLEMENTATION STACK:
   - Protein powder (whey or plant-based)
   - Creatine monohydrate: 5g daily
   - Omega-3 fatty acids: 2-3g daily
   - Vitamin D3: 2000-4000 IU daily
   - Magnesium: 300-400mg before bed
   - Optional: Beta-alanine (endurance), HMB (muscle preservation)
```

---

## 8. Program Generation Workflow

### Complete Process for Creating Personalized Programs

```
STEP-BY-STEP WORKFLOW:

1. COLLECT CLIENT DATA
   ✓ Complete client intake form with all placeholder data
   ✓ Assess current fitness level (baseline testing)
   ✓ Identify primary and secondary goals
   ✓ Determine training availability (days, time, equipment)
   ✓ Screen for injuries or limitations

2. SELECT PRIMARY PROMPT TEMPLATE
   ✓ Choose based on primary goal (Strength, Hypertrophy, Endurance, Hybrid)
   ✓ Adjust template for experience level (reduce volume for beginners)

3. INTEGRATE SECONDARY GOALS (if applicable)
   ✓ Use hybrid protocol guidelines
   ✓ Apply goal priority ratio (70/30 or 80/20)
   ✓ Structure training split to accommodate both goals

4. APPLY SPECIALIZED PROTOCOLS
   ✓ Add NBA Power Protocol if power/athleticism is a goal
   ✓ Integrate Biorhythm Nutrition based on training schedule
   ✓ Customize based on client preferences and constraints

5. GENERATE PROGRAM
   ✓ Use AI model with completed prompt OR
   ✓ Manually create program following template structure
   ✓ Include all required sections (warm-up, main work, cool-down)

6. REVIEW AND CUSTOMIZE
   ✓ Ensure appropriate volume for experience level
   ✓ Verify exercise selection matches available equipment
   ✓ Check that program addresses any limitations/injuries
   ✓ Confirm nutrition protocol aligns with training demands

7. FORMAT FOR DELIVERY
   ✓ Use workout-email-template.html for delivery
   ✓ Replace all {{placeholders}} with actual client data
   ✓ Include detailed exercise instructions
   ✓ Add progress tracking guidance

8. FOLLOW-UP PROTOCOL
   ✓ Check-in after Week 1 (form checks, difficulty assessment)
   ✓ Progress review at Week 4 (adjust as needed)
   ✓ Mid-program assessment at Week 6-8
   ✓ End-of-program testing and next program planning
```

---

## 9. Example Combination Scenarios

### Scenario 1: Strength + Conditioning
**Client:** 35-year-old male, intermediate, wants to get stronger but also improve cardiovascular health

**Approach:**
- Primary: Strength (70%) - 3-4 days heavy lifting
- Secondary: Conditioning (30%) - 2-3 days moderate cardio
- Use Strength Training template with added conditioning sessions
- Separate heavy leg days from running days by 24+ hours
- Nutrition: Higher calories on strength days, maintenance on cardio days

### Scenario 2: Hypertrophy + Athletic Power
**Client:** 28-year-old female, advanced, wants muscle definition and explosive power for sports

**Approach:**
- Block periodization: Alternate 4-week blocks
- Block 1: Hypertrophy focus (4x lifting, 1x power work)
- Block 2: NBA Power Protocol emphasis (3x power, 2x hypertrophy maintenance)
- Use Hypertrophy template for base, NBA Power Protocol for power blocks
- Nutrition: Caloric surplus during hypertrophy, maintenance during power blocks

### Scenario 3: Fat Loss + Muscle Preservation
**Client:** 42-year-old male, beginner-intermediate, wants to lose 20lbs while maintaining muscle

**Approach:**
- Primary: Resistance training 3-4x per week (preserve muscle)
- Secondary: Conditioning 3x per week (caloric expenditure)
- Use modified Hypertrophy template with reduced volume
- Biorhythm Nutrition in caloric deficit (-500 cal/day)
- High protein (2.4g/kg) to preserve muscle in deficit

### Scenario 4: Marathon Training + Strength Maintenance
**Client:** 30-year-old female, intermediate runner, training for marathon but wants to keep muscle

**Approach:**
- Primary: Endurance template (70%) - 4-5 days running
- Secondary: Strength maintenance (30%) - 2 days full-body lifting
- Schedule: Lift on easy run days or rest days
- Keep lifting volume minimal (6-9 sets per muscle group per week)
- Nutrition: High carb on long run days, higher protein on lifting days

---

## 10. Quality Control Checklist

Before delivering any program, verify:

- [ ] All {{placeholders}} have been replaced with actual client data
- [ ] Training frequency matches client availability
- [ ] Exercise selection matches available equipment
- [ ] Volume is appropriate for experience level
- [ ] Program addresses any stated injuries or limitations
- [ ] Progression model is clearly defined
- [ ] Deload weeks are included (every 3-6 weeks)
- [ ] Nutrition recommendations align with training goal
- [ ] Warm-up and cool-down protocols are included
- [ ] Exercise instructions include key technical cues
- [ ] Recovery recommendations are provided
- [ ] Contact information for support is included
- [ ] Program duration is clearly stated (8, 12, or 16 weeks)
- [ ] Success metrics and progress tracking methods are defined

---

## Notes on AI Model Usage

When using these prompts with AI models (GPT-4, Claude, etc.):

1. **Be specific:** Fill in all placeholders before submitting
2. **Provide context:** Include any relevant health history or preferences
3. **Request format:** Specify exact output format needed
4. **Iterate:** Review output and refine with follow-up prompts if needed
5. **Verify:** Always review AI-generated programs for safety and appropriateness

Example prompt to AI:
```
Using the Hypertrophy Prompt Template from program-generation-prompts.md, create a program for:
- Client: John Smith, 29-year-old male
- Experience: Intermediate (3 years training)
- Goal: Build muscle mass in upper body
- Availability: 5 days/week, 75 minutes per session
- Equipment: Full gym access
- Limitations: Previous left shoulder injury (avoid overhead pressing)
```

---

**Last Updated:** 2025-11-05
**Version:** 1.0
**Maintained by:** EliteFit Program Development Team