# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# Tic Tac Toe Game in React / เกมติ๊ก-แท็ก-โทใน React

## Overview / ภาพรวม
This is a simple Tic Tac Toe game built with React. The game allows two players to take turns marking spaces with either an 'X' or an 'O'. The game board is a 3x3 grid, and the first player to align three marks in a row, column, or diagonal wins. If all spaces are filled and no one has won, the game is a draw. The game can be reset at any time.

นี่คือเกมติ๊ก-แท็ก-โทที่สร้างด้วย React โดยผู้เล่น 2 คนสามารถผลัดกันวางเครื่องหมาย 'X' หรือ 'O' บนกระดาน 3x3 ผู้เล่นคนแรกที่ทำเครื่องหมายให้เรียงกันในแถว คอลัมน์ หรือเส้นทแยงมุมจะชนะ หากเต็มแล้วไม่มีผู้ชนะ เกมจะเสมอและสามารถรีเซ็ตได้ทุกเวลา

## Features / คุณสมบัติ
- **Turn-based gameplay**: The game alternates between 'X' and 'O' on each turn.
  - เกมเล่นตามเทิร์น: เกมจะสลับการเล่นระหว่าง 'X' และ 'O' ในแต่ละเทิร์น
- **Victory check**: The game automatically checks for a winner after each move.
  - การตรวจสอบผู้ชนะ: เกมจะตรวจสอบผู้ชนะหลังจากการเล่นแต่ละครั้ง
- **Reset button**: A reset button to restart the game at any time.
  - ปุ่มรีเซ็ต: ปุ่มที่ให้ผู้เล่นสามารถเริ่มเกมใหม่ได้ทุกเวลา

## Installation / การติดตั้ง
1. Clone the repository to your local machine.
   - คัดลอก repository นี้ลงในเครื่องของคุณ
   ```bash
   git clone https://github.com/KanittaJHA/Tic-Tac-Toe.git
