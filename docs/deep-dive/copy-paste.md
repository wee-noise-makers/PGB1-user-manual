# Copy & Paste

There are four elements that can be copied and pasted on the PGB-1 : Song
Parts, Tracks, Patterns, and Steps. Copying tracks means copying all patterns
of a track to another track, but this **does not** include track settings.
Copying patterns means copying all steps of a pattern to another pattern, this
**does** include pattern settings.

## Procedure

Start the copy/paste procedure, by holding the ++cpy-fx++ button down, and keep
it down during the entire procedure. Then select which kind of item you want to
copy by pressing one of the ++step++, ++pattern++, ++track++, or ++song++
buttons. The screen will now display the kind of element to copy, and two
"addresses": `From` and `To`. Addresses have between 1 and 3 identifiers: 1 for
song parts, and tracks, 2 for patterns (Track and Pattern), 3 for steps (Track,
Pattern, and Step).

![Copy Track](../assets/images/PGB1-OLED-copy-track.png)
![Copy Pattern](../assets/images/PGB1-OLED-copy-pattern.png)
![Copy Step](../assets/images/PGB1-OLED-copy-step.png)

| Element | Address Format | On screen |
|---------|----------------|-----------|
| Song Part | Part number | e.g. `01` |
| Track | Track number | e.g. `T01` |
| Pattern | Track + Pattern | e.g. `T01-P03` |
| Step | Track + Pattern + Step | e.g. `T01-P03-S05`|


In the `From` address, two blinking question marks (`??`) indicate the
identifier to enter, press one button from ++1++ to ++16++ to set it. This is
what will be copied. Now, there are two blinking question marks on the
`To` address, press one button from ++1++ to ++16++ to select where to
copy. The copy/paste is done immediately.

After the first paste, the "To" address shows blinking question marks again.
You can immediately paste to another destination without re-selecting the
source.

## Changing Address Components

When copying patterns or steps, the addresses starts with your current track
and pattern automatically set. Blinking question marks indicate what to enter
next.

You may need to change the track or pattern before entering the final number:

- Press ++track++ to enter/change the track number
- Press ++pattern++ to enter/change the pattern number

For example the following sequence will copy step 2 from pattern 5 of track 7,
to step 9 from pattern 3 of track 1:

++cpy-fx++ -> ++step++, ++track++, ++5++, ++7++, ++2++, ++track++, ++7++,
++3++, ++9++

## Examples

### Copy Step 2 to Steps 4, 6, and 8 (Same Pattern)

1. Hold ++cpy-fx++ + press ++step++
2. Press ++2++ (source step)
3. Press ++4++ (first destination)
4. Press ++6++ (second destination)
5. Press ++8++ (third destination)
6. Release ++cpy-fx++

### Copy Step from Track 7, Pattern 5, Step 2 to Track 1, Pattern 3, Step 9

1. Hold ++cpy-fx++ + press ++step++
2. Press ++track++, then ++7++ (source track)
3. Press ++5++ (source pattern)
4. Press ++2++ (source step)
5. Press ++track++, then ++1++ (dest track)
6. Press ++3++ (dest pattern)
7. Press ++9++ (dest step)
8. Release ++cpy-fx++

### Copy Pattern 1 to Patterns 2, 3, 4 (Same Track)

1. Hold ++cpy-fx++ + press ++pattern++
2. Press ++1++ (source pattern)
3. Press ++2++ (first destination)
4. Press ++3++ (second destination)
5. Press ++4++ (third destination)
6. Release ++cpy-fx++

## Tips

### Step Templates

1. Configure a step with desired settings
2. Copy to multiple steps quickly
3. Adjust notes/conditions as needed
