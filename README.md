# Pong (퐁)

&lt;레트로의 유니티 게임 프로그래밍 에센스 6> 4th Hands-on Project

## 🎮 Game Overview

A remake of the classic Pong game, supporting two players in a networked multiplayer environment.

## 🎯 Implementation Highlights

- **Unity Netcode for GameObjects** for two-player networked multiplayer
- **Listen server architecture** and **server-authoritative logic** to ensure fair and consistent gameplay
- **NetworkVariables** to sync paddle positions, ball state, score, etc.
- **ClientRpc** and **ServerRpc** to handle events like "start game" or "restart"
- **NetworkSceneManager** for scene transitions and lobby-to-game flow

## 📸 Screenshots

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/2d6a0933-4ff8-462f-80fd-6ba6b35e73bf" />
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/9c80d1eb-ae03-4ed0-a736-9616bbfbb1c2" />
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/b48703f9-3aa1-40b3-9450-47bd0cefc2ca" />
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/64bff53a-6c28-4f4d-9f20-7f2aa0957959" />

## 🔧 Tech Stack

- Unity 6000.0.36f1
