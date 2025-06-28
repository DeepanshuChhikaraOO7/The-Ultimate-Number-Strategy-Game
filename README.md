# The Ultimate Number Strategy Game 🎮

[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue.svg)](https://python.org)  
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

```ascii
█░█ █▄░█ █▀█ █▀▀ █▄░█ █▀▄ ▀█▀ 
█▀█ █░▀█ █▀▄ ██▄ █░▀█ █▄▀ ░█░ 

█▄█ █▀█ ▄▀█ █▀█ █▀▀ █░█ █▀▀ ▀█▀ █▀▀ 
░█░ █▀▄ █▀█ █▀▄ ██▄ █▀█ █▄▄ ░█░ ██▄
```

A strategic multiplayer number guessing game where players compete to get closest to a target number while trying to predict their opponents' choices.

## 🙏 Acknowledgments

- Inspired by Alice in borderland season 2 King of Diamonds Game (Math Game)
- Built with Python and Colorama
- Special thanks to all contributors

## 🌟 Features

- 🎯 Multiple difficulty levels
- 👥 Support for up to 5 players
- 🎨 Colorful console interface
- 🔊 Interactive sound effects
- 📊 Game history and replay system
- 💫 Dynamic player elimination system
- 📈 Real-time score tracking

## 🎮 Game Rules

1. Multiple players compete in rounds
2. Each player selects a number between 0 and 100
3. Target is calculated as a percentage of the average (varies by difficulty)
4. The player closest to the target wins the round
5. Other players get -1 point
6. Players are eliminated at -5 points
7. Last player standing wins!

## 🔥 Difficulty Levels

| Level    | Rounds | Target Calculation | Challenge                    |
|----------|--------|-------------------|------------------------------|
| Easy     | 5      | 80% of average    | Beginner friendly           |
| Medium   | 7      | 70% of average    | Increased complexity        |
| Hard     | 10     | 60% of average    | For strategic masterminds   |

## 🎯 How to Play

1. Start the game and select difficulty
2. Enter names for all players
3. Each round:
   - Players enter numbers between 0-100
   - Game calculates the target number
   - Closest player wins the round
   - Other players lose points
4. Avoid elimination by keeping your score above -5
5. Last player standing wins!

## 💡 Strategy Tips

- Think about what others might choose
- Consider the psychology of other players
- Watch for patterns in opponents' choices
- Adapt your strategy based on remaining players
- Balance risk and safety in your number choices

## 🖥️ Game Interface

The game features a colorful and intuitive console interface:
- 🟢 **Green**: Success messages and positive scores
- 🔴 **Red**: Elimination messages and negative scores
- 🟡 **Yellow**: Warnings and important information
- 🔵 **Cyan**: Player turns and game progress

## 📊 Game History

- Each game session is recorded
- Replay files are saved with timestamps
- Track player performance and strategies
- Analyze winning patterns

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by **Deepanshu Chhikara**
