# Claude Buddy

**Claude Buddy** is a playful companion system built into Claude Code — a lightweight AI pet that lives right beside your input box, quietly observing your work and occasionally offering thoughts.

> Type `/buddy` to activate your Buddy and meet your personalized AI companion.

---

<img width="2660" height="1812" alt="image" src="https://github.com/user-attachments/assets/f92d63c0-09f6-4610-8628-9bec427b19e1" />

## 🧠 What is Claude Buddy?

[Claude Buddy](https://claudebuddy.app/) is a **Tamagotchi-style AI companion system** designed to bring personality and delight into your coding workflow.

Once activated, your Buddy appears next to your input field, rendered in ASCII art, and behaves like a subtle observer rather than the main assistant.

- Lives inside your Claude Code terminal  
- Acts as a **side companion**, not the main AI  
- Speaks through **speech bubbles**  
- Responds only when you call its name  
- Keeps responses **short (one line max)**  

---

## ✨ Key Features

### 🐾 Personalized Companion
When you run `/buddy`, Claude generates a unique pet based on your conversation history.

- Each Buddy has a **name and personality**
- Generated once at "hatching" and stored permanently
- Example: A penguin named *Crumpet* 🐧

---

### 🎲 18 Unique Species

Duck, Goose, Blob, Cat, Dragon, Octopus, Owl, Penguin, Turtle, Snail, Ghost, Axolotl, Capybara, Cactus, Robot, Rabbit, Mushroom, Chonk

---

### 💎 Rarity System

| Rarity      | Probability |
|------------|------------|
| Common     | 60%        |
| Uncommon   | 25%        |
| Rare       | 10%        |
| Epic       | 4%         |
| Legendary  | 1%         |

✨ Plus a **1% chance to be Shiny**

---

### 🧬 Attribute System

Each Buddy has 5 core attributes (range: 1–100):

- Debugging
- Patience
- Chaos
- Wisdom
- Snark

---

## ⚙️ How It Works

### 🧩 Dual-System Architecture

#### Bones (Deterministic)
Generated from `hash(userId) + salt`

#### Soul (Generated Once)
Includes name, personality, and timestamp

---

## 🎮 Interaction

- Activate: `/buddy`
- Call by name
- Pet: `/buddy pet`

---

## 🌐 Website

- Domain: [https://claudebuddy.app  ](https://claudebuddy.app/)
- Email: support@claudebuddy.app  
