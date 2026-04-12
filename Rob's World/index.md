---
title: Rob's World
tags: [home, index, moc]
---

# Home — According to Pfineas

*D&D 3.5 Campaign | DM: Robert | Sessions every two weeks*

> [!info] You Are Playing
> **[[Pfineas Starmantle]]** — Level 3 Wizard, Moon Elf
> Substituting for Andrew (Brent Isherwood's character)
> Current XP: **8,784** / 12,000 (next level)

---

## Quick Navigation

### 🧙 Characters
- [[Pfineas Starmantle]] — Full character sheet (stats, weapons, feats, equipment)
- [[Labraen]] — Owl familiar ("Lizard Slayer")

### 📖 Spells
- [[Spellbook]] — Complete spell list with PH page references and components
- [[Spell Memorization Log]] — Session-by-session spell usage (from pink notepad)

### ⚔️ Party
- [[The Xterminators]] — Party info, Concordium, responsibilities, bank & finances

### 🎯 XP
- [[XP Log]] — Individual XP tracking, session records

### 🔗 Resources
- [[Important Links]] — All campaign links (character sheets, documents, spreadsheets)

---

## Session Checklist

Before each session:
- [ ] Review [[Spellbook]] and decide memorized spells
- [ ] Check [[The Xterminators]] for marching & watch order duties
- [ ] Confirm HP and current spell slots

After each session:
- [ ] Update [[Spell Memorization Log]] with spells cast
- [ ] Update [Pfineas XP Sheet](https://www.icloud.com/numbers/0a3IBkYhUNBx9YGfK89xFMsIA) with table XP
- [ ] Update [[XP Log]] here for reference
- [ ] Update marching order and watch order on the dry erase board

---

## Campaign Notes

- Sessions occur every **two weeks**
- DM Robert is a rules lawyer — he puts 5–10 hours into rules research between sessions
- Pfineas is the party **Administrator** per the Concordium (though Pete/Garreck maintains the bank)
- The official XP and bank records are the **online iCloud spreadsheets** — not paper
- Flying movement rules supplement: [robsworld.org PDF](https://www.robsworld.org/Flying%20-%20Movement%20&%20Maneuverabi.pdf) (ref DMG pg 20)

## Technology
setting up Git Repo: https://quartz.jzhao.xyz/setting-up-your-GitHub-repository
setting up hosting: https://quartz.jzhao.xyz/hosting
authored in Obsidian: https://obsidian.md/

`npx quartz sync` is the command to update the Repo
### Deployment workflow:

```
Edit in Obsidian
      ↓
Obsidian Git auto-pushes → v4 (preview)
      ↓
Happy with preview?
      ↓
git checkout main
git merge v4
git push origin main    ← triggers production deploy
git checkout v4         ← go back to working branch
```

And for Quartz framework updates:

```bash
git checkout v4
git fetch upstream
git merge upstream/v4   ← test in preview first
git checkout main
git merge v4            ← promote to prod when confirmed working
```