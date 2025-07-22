# the millioner
1winer
<title>3-в-1 Игры</title> <style> body { font-family: sans-serif; background: linear-gradient(to bottom right, #0f0f0f, #1e1e1e); color: #fff; display: flex; flex-direction: column; align-items: center; padding: 30px; }
h1 {
  margin-bottom: 20px;
}

.game-selection {
  margin-bottom: 20px;
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  justify-content: center;
}

.game-selection button,
.buttons button {
  margin: 0 10px;
  padding: 10px 20px;
  font-size: 16px;
  border-radius: 8px;
  border: none;
  cursor: pointer;
  background: linear-gradient(145deg, #444, #222);
  color: white;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
  transition: all 0.3s ease;
}

.game-selection button:hover,
.buttons button:hover {
  background: linear-gradient(145deg, #666, #333);
  transform: scale(1.05);
}

.grid {
  display: grid;
  grid-template-columns: repeat(5, 50px);
  gap: 8px;
  margin-bottom: 20px;
}

.cell {
  width: 50px;
  height: 50px;
  background-color: #2b2b2b;
  border: 2px solid #000000;
  border-radius: 6px;
  cursor: pointer;
  font-size: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: background 0.6s ease, box-shadow 0.6s ease, transform 0.6s ease;
  opacity: 0;
}

.cell.visible {
  opacity: 1;
  transform: scale(1.1);
}

.cell.open {
  background-color: #444;
}

.cell.bomb {
  background-color: #8b0000;
}

.cell.open.glow {
  box-shadow: 0 0 10px 3px #f0f000;
  background-color: #555;
}

.mine-settings {
  margin-bottom: 10px;
  color: #ccc;
  display: flex;
  gap: 10px;
  align-items: center;
  justify-content: center;
}

.mine-settings label {
  margin-right: 5px;
}

.back-button {
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
}
</style>
