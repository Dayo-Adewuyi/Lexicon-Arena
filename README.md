# Lexicon Arena

A strategic turn-based word battle game built on Arbitrum where players compete using vocabulary and tactical thinking.

## Overview

Lexicon Arena is a unique blockchain game that combines word creation with strategic grid-based combat. Players battle on 5x5 grids, forming words to launch attacks, defend positions, and manage resources in an engaging turn-based format.

## Game Mechanics

### Grid System
- Each player manages a 5x5 letter grid
- Letters can form words horizontally, vertically, and diagonally
- Special cell positions provide bonus effects
- Grid cells can be damaged, corrupted, or protected

### Core Gameplay Loop
1. Players receive random letters and energy points at the start of each turn
2. Actions available per turn:
   - Place letters on the grid
   - Activate words for effects
   - Use special abilities
   - Manage defenses
3. Turn timer ensures fast-paced gameplay
4. Victory achieved through strategic grid control and point accumulation

### Word Effects

#### Attack Words
- Damage opponent's grid cells
- Different damage types:
  - Direct Damage: Immediate cell corruption
  - Poison Damage: Spreading corruption
  - Scramble Damage: Letter rearrangement
  - Lock Damage: Cell freezing

#### Defense Words
- Protect cells from damage
- Create shields and barriers
- Heal corrupted cells
- Counter opponent's effects

#### Utility Words
- Generate energy points
- Activate special abilities
- Enhance other word effects
- Manipulate the grid state

### Strategic Elements
- Word length affects power level
- Intersecting words create combos
- Rare letters (Q, X, Z) provide powerful effects
- Resource management crucial for success
- Position-based tactical decisions

## Technical Architecture

#### Battle Flow
1. Game initialization
2. Turn-based action resolution
3. Effect processing
4. Victory condition checking
5. State updates

### Frontend Integration
- Real-time grid visualization
- Word validation system
- Effect animation handling
- Turn timer display
- Battle state management

## Getting Started


### Installation
```bash
# Clone repository
git clone https://github.com/dayo-adewuyi/lexicon-arena

# Install dependencies
cd lexicon-arena
npm install

# Configure environment
cp .env.example .env
# Add your environment variables

# Run tests
npx hardhat test

# Deploy contracts
npx hardhat run scripts/deploy.js --network arbitrum
```



## Game Modes

### Ranked Matches
- Competitive ladder system
- Seasonal rankings
- Skill-based matchmaking
- Rewards for top players

### Casual Play
- Practice mode
- Custom games with friends
- Daily challenges
- Tutorial battles

### Tournaments
- Regular competitions
- Special rule sets
- Prize pools
- Team battles

## Educational Integration

### Learning Features
- Vocabulary expansion
- Strategic thinking development
- Resource management skills
- Time management practice

### Classroom Support
- Custom word lists
- Class tournaments
- Progress tracking
- Educational achievements

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on:
- Code style
- Pull request process
- Development workflow
- Testing requirements

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Discord: [Join our community](https://discord.gg/lexiconarena)
- Twitter: [@LexiconArena](https://twitter.com/lexiconarena)
- Email: support@lexiconarena.com
