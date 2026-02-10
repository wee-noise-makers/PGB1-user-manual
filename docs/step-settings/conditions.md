# Trigger Conditions

Trigger conditions determine when a step plays, adding variation and complexity to your patterns.

## Accessing Conditions

1. Enter Step Mode (press ++step++)
2. Select a step
3. Navigate to page 1 (Condition)
4. Use ++up++ / ++down++ to change the condition

## Available Conditions

### Never

The step never plays. Useful for temporarily disabling steps without removing them.

### Probability Conditions

| Condition | Description |
|-----------|-------------|
| 25% | Step plays 25% of the time |
| 50% | Step plays 50% of the time |
| 75% | Step plays 75% of the time |

Each time the sequencer reaches this step, a random check determines if it plays.

### Always

The step always plays (default). Use for notes that should play every time.

### Fill Conditions

| Condition | Description |
|-----------|-------------|
| Fill | Only plays when a Fill FX is active |
| Not Fill | Only plays when Fill FX is NOT active |

These work with the Live FX Fill modes.

### Repeat Conditions

Repeat conditions let you trigger a step on specific pattern loops within a cycle. The format is **X:Y** where:

- **Y** = the cycle length (how many loops before the pattern repeats)
- **X** = which loop within the cycle triggers the step

For example, **2:3** means "play on loop 2 of every 3 loops."

#### Available Repeat Conditions

| Condition | Loop 1 | Loop 2 | Loop 3 | Loop 4 | Then repeats... |
|-----------|:------:|:------:|:------:|:------:|-----------------|
| 1:2       | ✓      | ·      | ✓      | ·      | every 2 loops   |
| 2:2       | ·      | ✓      | ·      | ✓      | every 2 loops   |
| 1:3       | ✓      | ·      | ·      | ✓      | every 3 loops   |
| 2:3       | ·      | ✓      | ·      | ·      | every 3 loops   |
| 3:3       | ·      | ·      | ✓      | ·      | every 3 loops   |
| 1:4       | ✓      | ·      | ·      | ·      | every 4 loops   |
| 2:4       | ·      | ✓      | ·      | ·      | every 4 loops   |
| 3:4       | ·      | ·      | ✓      | ·      | every 4 loops   |
| 4:4       | ·      | ·      | ·      | ✓      | every 4 loops   |

(✓ = step plays, · = step is skipped)

#### Practical Examples

**Alternating notes (1:2 and 2:2)**

Put two different notes on the same step position using parameter locks:

- Step 5 with note C, condition 1:2
- Step 5 with note E, condition 2:2

Result: the step alternates between C and E on each loop.

**Building variation over 4 bars**

- Main hi-hat pattern: Always condition
- Extra accent on step 8: condition 4:4

Result: the accent only plays every 4th loop, creating a longer phrase.

**Complementary patterns (1:3, 2:3, 3:3)**

Use all three conditions on different tracks or notes to create interlocking parts that together form a complete cycle every 3 loops.

These are useful for creating variation over multiple loops without changing patterns.

## Using Conditions Creatively

### Ghost Notes

1. Add hi-hat or snare steps
2. Set condition to 50% or 75%
3. Set velocity low
4. Creates subtle, varying ghost notes

### Building Patterns

1. Create a base pattern with "Always" conditions
2. Add additional steps with "Fill" condition
3. Activate Fill FX to trigger the extra steps

### Long Form Variation

1. Use 1:2, 1:3, 1:4 conditions on different steps
2. Pattern sounds different each time it loops
3. Creates interest over 4-8 bar sections

### Call and Response

1. First half of pattern: Always condition
2. Second half: 50% condition
3. Creates varying responses to consistent phrases

## Tips

- Copy steps with conditions to quickly build complex patterns
- Combine multiple probability steps for layered variation
- Use Fill conditions to add controlled complexity during performance
- 1:4 conditions work great for accents every 4th loop
