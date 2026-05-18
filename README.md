# FallConsensus

**Sovereign Mesh Governance**

WebRTC peer-to-peer decision-making engine. No central server. 7-dimension bloom vectors. Cosine similarity convergence detection.

## Features

- WebRTC mesh via PeerJS — fully decentralised, no server needed
- 7-dimension bloom voting (mapped to prime spine {2,3,5,7,11,13,17})
- Cosine similarity consensus detection (avg >= 70%, min pairwise >= 50%, variance < 0.15)
- Real-time peer ring visualisation
- Similarity matrix across all participants
- Decision history with convergence metrics
- BroadcastChannel for local device coordination
- Works across any number of participants

## How It Works

1. Create or join a room
2. Someone proposes a decision
3. Each participant rates across 7 dimensions
4. System detects convergence automatically
5. Consensus reached when bloom vectors align

No voting. No majority rule. Alignment detected, not enforced.

## Run

Double-click `FallConsensus.html`. Share the room code. Decide together.

---

Part of the Fall tool suite. Governance without hierarchy.
