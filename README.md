# Chess Master - Standalone Single-File Web Application

A completely self-contained, standalone Chess web application featuring an intelligent AI opponent with 4 difficulty levels, complete standard FIDE chess rules, move history, PGN/FEN export, and procedural Web Audio sound effects.

---

## ⚡ Zero Setup / Direct Double-Click

This version of `index.html` is **100% self-contained into a single file**:
- **No HTTP server needed**: Simply double-click `index.html` anywhere on your computer to play.
- **No build steps**: Pure vanilla HTML5, CSS3, and JavaScript.
- **No external dependencies**: Vector SVG pieces and procedural Web Audio effects are bundled directly inside.
- **Works offline**: Take `index.html` on a USB drive, email it, or open it in any browser (Chrome, Edge, Firefox, Safari).

---

## 🌟 Key Features

- **Intelligent AI Opponent**:
  - Minimax search with Alpha-Beta pruning, MVV-LVA move ordering, Piece-Square Tables (PST), and Quiescence search.
  - 4 scalable difficulty presets: Novice (Level 1), Casual (Level 2), Intermediate (Level 3), and Advanced (Level 4).
- **Full Standard Chess Rules**:
  - En Passant captures.
  - Kingside and Queenside castling with through-check validation.
  - Pawn promotion modal selection (Queen, Rook, Bishop, Knight).
  - Checkmate and Stalemate detection.
  - 50-move rule, threefold repetition, and insufficient material draws.
- **Modern User Experience**:
  - Dual input: fluid drag-and-drop + tap/click-to-move.
  - Visual indicators: Selected square, legal move dots/capture rings, last move highlights, king-in-check pulse.
  - Dynamic captured pieces tray and material balance score ($+3$, $+1$, etc.).
  - Move history with Standard Algebraic Notation (SAN), e.g., `1. e4 e5 2. Nf3 Nc6`.
  - Board flip (White / Black perspective).
  - Take back / Undo move functionality.
  - PGN export and FEN copy to clipboard.
- **Procedural Audio**:
  - Synthesized Web Audio API sound effects for piece moves, captures, castling, check chimes, and victory/defeat tones.

---

## 🌐 Available Online

This single static file is available online on page https://fcsaba-chess.netlify.app/.
