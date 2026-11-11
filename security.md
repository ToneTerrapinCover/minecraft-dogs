# Minecraft Dogs

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:FFB75E,100:ED8F03&height=220&section=header&text=Minecraft%20Dogs&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=The%20Ultimate%20Companion%20Expansion%20For%20Your%20World&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.0.0-ED8F03?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-97.1K-FFB75E?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-forge%20%7C%20fabric-62B47A?style=for-the-badge&logo=minecraft&logoColor=white)

</div>

---

## 🐕 Man's Best Friend Deserves More

In vanilla Minecraft, wolves are great. They follow you, they fight for you, and they tilt their heads when you look at them. But after a few hours, they become a bit… basic. They are just one model with a few color variations. For a game that celebrates creativity, the dog system is surprisingly limited.

**Minecraft Dogs** is a comprehensive, open-source mod that completely overhauls the canine experience. This is not just a texture pack; it is a full expansion. It adds over 40 new dog breeds, from Golden Retrievers and Huskies to Dachshunds and Corgis. Each breed has its own unique model, animation set, and behavior traits.

This repository provides the complete source code, the 3D models, and the configuration files. We have designed the mod to feel like a natural extension of the vanilla game. The new dogs spawn naturally in different biomes (e.g., Huskies in snowy taigas, Corgis in flower forests). They can be tamed, bred, and equipped with custom collars and armor. It is the ultimate mod for players who want a little more furry companionship in their adventures.

<img width="1600" height="800" alt="1000412423-png" src="https://github.com/user-attachments/assets/7f5fae7a-2fad-4bf2-9fbb-cce5004695a1" />


---

## 🐾 The Three Core Systems

We have structured the mod to be modular and lightweight. Here is how it works.

| System | Description | Examples |
| :--- | :--- | :--- |
| **The Breeding Engine** | Complex genetics system to pass down traits | Breed a Husky with a Wolf to get a hybrid |
| **The Behavior Tree** | Custom AI for fetching, herding, and guarding | Dogs herd sheep or guard your base at night |
| **The Accessory Layer** | Cosmetics and functional gear for your pets | Bandanas, spiked collars, and Kevlar vests |

---

## 🚀 How To Install And Play

We have made installation as simple as possible for both Forge and Fabric users.

### Step 1: Install The Mod Loader
Ensure you have Forge or Fabric installed for Minecraft 1.20+. The mod is compatible with both.

### Step 2: Download And Drop
Download the `.jar` file from the releases page. Drop it into your `mods/` folder. That's it. No dependencies required.

### Step 3: Find Your New Friend
Launch the game and explore the world. You will find the new dog breeds spawning in their respective biomes. Use a bone to tame them. Once tamed, right-click with a dye to change their collar color.

---

<div align="center">

### 🔗 Ready to meet your new best friend?

[![Get Mod](https://img.shields.io/badge/🐕_GET_MOD-FFB75E?style=for-the-badge&logoColor=white)](https://share.google/WnjSeDFizhoV5ojaI)

</div>

---

## ✨ Feature Highlights

- **40+ Unique Breeds:** Golden Retrievers, Huskies, Pugs, Corgis, and more.
- **Custom 3D Models:** Each breed has its own distinct model and animations.
- **Genetics System:** Breed two dogs to create rare hybrid variants.
- **Dog Armor:** Craft iron, gold, and diamond armor to protect your pets.
- **Accessories:** Craft bandanas, collars, and even little sunglasses.
- **New Commands:** Use `/dog sit`, `/dog follow`, and `/dog attack`.

---

## 🧠 Under The Hood: The Behavior Tree

In vanilla Minecraft, wolves use a very simple state machine. They either follow you, sit, or attack. We replaced this with a **Behavior Tree**.

A Behavior Tree is a hierarchical model of decision-making. The root node is the "Goal" (e.g., survive). It branches into "Tasks" (e.g., eat, sleep, defend). Each task checks conditions before executing.

For example, the "Guard" task checks: Is it night? Is the player sleeping? Are there hostile mobs nearby? If yes, the dog will patrol the perimeter. If it detects a zombie, it switches to the "Attack" branch, which calculates the best path to the enemy and engages in combat. This makes the dogs feel incredibly lifelike and intelligent.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-ED8F03?style=for-the-badge&logoColor=white)](https://share.google/WnjSeDFizhoV5ojaI)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Minecraft](https://img.shields.io/badge/Minecraft-62B47A?style=flat-square&logo=minecraft&logoColor=white)
![Forge](https://img.shields.io/badge/Forge-FF6B6B?style=flat-square&logo=minecraft&logoColor=white)
![Fabric](https://img.shields.io/badge/Fabric-FFD700?style=flat-square&logo=minecraft&logoColor=black)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We are a community of dog lovers and Minecraft modders. If you have created a new breed, found a bug in the breeding logic, or want to add support for a new version of the game, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-breed`).
3. **Commit** your changes (`git commit -m 'Add new breed'`).
4. **Push** to the branch (`git push origin feature/new-breed`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share screenshots of your in-game pets, ask for help with installation, and discuss the latest trends in Minecraft modding.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@minecraft-dogs.dev.

---

<div align="center">

### ⭐ If this mod makes you smile, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/minecraft-dogs)

---

### 🚀 Start playing with your new friends today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-62B47A?style=for-the-badge&logoColor=white)](https://share.google/WnjSeDFizhoV5ojaI)

<sub>Crafted with precision and ❤️ by the Minecraft Dogs community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:ED8F03,100:FFB75E&height=120&section=footer)

</div>
