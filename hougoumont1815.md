## Hougoumont 1815 Tabletop Miniatures Game Rules

### 1. Game Phases
1. **Give Orders**
2. **Movement**
3. **Firing** (Artillery, then Small Arms)
4. **Melee**
5. **Morale Check**
6. **Repeat**

### 2. Movement
- **Infantry**: 8 inches per turn.
- **Light Infantry**: 8 inches per turn; no movement penalty in woods.
- **Line Infantry**: 6 inches per turn in woods; 8 inches per turn elsewhere.
- **Artillery**: 4 inches per turn; cannot enter woods.
- **Cavalry**: 16 inches per turn; cannot enter woods.
- **Charge Bonus**: +2 inches for infantry, +4 inches for cavalry.

### 3. Firing
#### 3.1. Small Arms
- Each figure rolls a D20.
- Hit if D20 roll ≥ distance in inches.
- Light Infantry: +2 to D20 roll.
- Rifles: +5 to D20 roll.
- Firing into woods: +2 needed to hit.
- Firing at targets behind walls/buildings: +10 needed to hit.

#### 3.2. Artillery
- Flat Trajectory Artillery: Roll 3D20.
  - Hit if sum ≥ distance in inches.
  - Against buildings: needs additional 9 points to penetrate.
  - Building fire chance: 1/3 on D6 (5 or 6 means fire).
- Howitzer Artillery: Roll 2D6.
  - 7: Direct hit.
  - 6: 1 inch short.
  - 8: 1 inch far.
  - Direct hit: Roll D4 for damage.
  - 1 inch off: 1 hit.
  - More than 1 inch off: No effect.
  - Minimum range: 7 inches.
  - Howitzer veterans: Adjust roll by 1.
  - Howitzer elite: Adjust roll by 2.
  - Consecutive turn on stationary target: +1 adjust to 2D6 roll.
- Canister Fire: Within 20 inches, roll D8 for damage.
  - Against woods or walls/buildings: Roll D6 for damage instead of D8.

**Note:** Artillery inflicted casualties are taken into account before small arms fire is computed.

#### 3.3. Prohibited Actions
- **Artillery Firing into Melee**: Artillery units are prohibited from firing into ongoing melee engagements to prevent friendly fire casualties.

#### 3.4. Flanking
- A unit is considered flanked if attacked from the side or rear.
- Flanked units must take an immediate morale check with a -3 modifier.
- Flanking attacks bypass cover bonuses for the flanked unit.

### 4. Melee
#### 4.1. Melee Engagement
- Each figure rolls a D20.
- Modifiers:
  - Experienced: +2.
  - Veteran: +3.
  - Elite: +5.

#### 4.2. Calculating Melee Casualties
1. **Total Melee Scores**:
   $$ \text{Total Score}_{\text{Side A}} = \text{Number of Figures} \times (\text{Average D20 Roll} + \text{Modifier}) $$
   $$ \text{Total Score}_{\text{Side B}} = \text{Number of Figures} \times (\text{Average D20 Roll} + \text{Modifier}) $$
2. **Calculate the Difference**:
   $$ \text{Difference} = \left| \text{Total Score}_{\text{Side A}} - \text{Total Score}_{\text{Side B}} \right| $$
3. **Casualty Calculation**:
   - Casualties for the losing side are proportional to the score difference.
   - Formula:
     $$
     \text{Casualties for Side A} = \left( \frac{\text{Total Score Difference}}{\text{Effective Score per Figure}} \right)
     $$
   - Effective Score per Figure is based on the average roll and modifiers.

### 5. Morale Check
- Roll D20; compare to morale threshold.
  - Inexperienced: -2.
  - Experienced: No modifier.
  - Veteran: +2.
  - Elite: +4.
- Situations triggering morale checks:
  - Unit takes 25% or more casualties in a single phase.
  - Unit falls below half strength.
  - Unit is flanked.
- **If a unit fails a morale check**:
  - **Retreat**: The unit must immediately move 8 inches away from the enemy and take no further action this turn.
  - **Rally Attempt**: In the next Give Orders phase, the unit may attempt to rally by rolling a D20. If the roll is successful (meeting or exceeding the morale threshold), the unit rallies and can act normally. If it fails, it continues to retreat 8 inches per turn until it rallies or exits the battlefield.
  - **Shattered**: If a unit that has failed a morale check takes another hit before successfully rallying, it is shattered and removed from the game.

### 6. Special Rules
#### 6.1. Buildings
- Artillery against buildings needs additional 9 points on 3D20 to penetrate.
- Building fire chance: 1/3 on D6 (5 or 6 means fire).
- Howitzer fire:
  - Direct hit: Blows the roof off.
  - Remove the roof model.
  - Subsequent hits calculate regular howitzer damage.
  - Apply building fire check.

#### 6.2. Light Infantry in Skirmish Formation
- **Movement**: Light infantry in skirmish formation can move 8 inches per turn, ignoring terrain penalties (including woods).
- **Cover Bonus**: Light infantry in skirmish formation receive an additional +2 to their D20 roll to hit them.
- **Firing**: Light infantry in skirmish formation can spread out and fire more effectively:
  - Each figure rolls a D20 with a +1 modifier.
  - Light Infantry: +2 to D20 roll, total of +3 in skirmish formation.

### 7. Summary
- **Phases**: Give Orders, Movement, Firing, Melee, Morale Check, Repeat.
- **Movement**: Infantry 8 inches, Light Infantry 8 inches, Line Infantry 6 inches in woods, Artillery 4 inches, Cavalry 16 inches.
- **Firing**: D20 roll for small arms, 3D20 for artillery, 2D6 for howitzer.
- **Melee**: D20 roll per figure with modifiers.
- **Morale**: D20 roll with modifiers based on unit experience.