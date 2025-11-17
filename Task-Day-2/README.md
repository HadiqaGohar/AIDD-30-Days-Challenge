# AIDD 30-Day Challenge – Task 2 Official Submission  
**.md format (ready to submit)**  

**Student Name:** [Your Full Name]  
**GitHub Repo Link:** https://github.com/yourusername/aidd-30day-task2  

---

### Part A — Theory (Short Questions) – Apne lafzon mein

**1. Nine Pillars Understanding**  
- Q: Why is using AI Development Agents (like Gemini CLI) for repetitive setup tasks better for your growth as a system architect?  
  Jawab: Jab hum Gemini CLI ya Claude Code jaise agents se boring setup tasks (jaise project scaffolding, config files, boilerplate) karwa lete hain to humara time aur dimaag bach jata hai. Is free time mein hum architecture design, system layering, scalability aur trade-offs par focus kar sakte hain. Ye practice humein chhoti-chhoti cheezon mein nahi uljhaati, balke bade level ka sochne ki aadat daalti hai — jo ek real system architect ki asli skill hoti hai.

- Q: Explain how the Nine Pillars of AIDD help a developer grow into an M-Shaped Developer.  
  Jawab: Nine Pillars (TDD, AI CLI, MCP, agents, specs, etc.) milkar ek aisa complete ecosystem banate hain jisse ek hi developer poori team ki tarah kaam kar sakta hai. Agent boring cheezen handle karte hain, specs clear direction dete hain, aur TDD quality rakhta hai. Is wajah se developer ko har cheez mein average hone ki zaroorat nahi — wo 2-4 related fields mein bohot deep ja sakta hai (jaise system design + DevOps + prompting + security) aur baqi gaps AI fill kar deta hai. Yehi M-shaped developer banata hai.

**2. Vibe Coding vs Specification-Driven Development**  
- Q: Why does Vibe Coding usually create problems after one week?  
  Jawab: Vibe coding mein hum bina plan ya spec ke “feel” ke saath code likhte jaate hain. Shuru mein mazaa aata hai aur jaldi code ban jata hai, lekin ek haftay baad jab nayi feature add karni ho ya bug fix karna ho to samajh nahi aata ke system kis tarah connected hai. Architecture messy ho jata hai, duplication badh jata hai aur chhoti si change bhi bohot dard deti hai.

- Q: How would Specification-Driven Development prevent those problems?  
  Jawab: SDD mein pehle hum clear, executable specification likhte hain (behavior, edge cases, error messages sab likha hota hai). AI ya hum usi spec ke mutabiq code banate hain. Jab specification pehle se solid hoti hai to code already well-structured hota hai, baad mein changes karna aasaan hota hai aur koi bhi naya banda ya agent bhi foran samajh jata hai ke kya karna hai.

**3. Architecture Thinking**  
- Q: How does architecture-first thinking change the role of a developer in AIDD?  
  Jawab: Pehle developer sirf code likhne wala hota tha. Architecture-first thinking ke saath developer ab “system designer” ban jata hai. Wo decide karta hai ke kaunsa layer kya karega, agents ko kya task dena hai, spec kaisi honi chahiye — coding to bas last step ban jata hai jo agent bhi kar sakta hai.

- Q: Explain why developers must think in layers and systems instead of raw code.  
  Jawab: Raw code likhna kisi bhi AI tool se 10 second mein ho jata hai. Asli value ab ye hai ke system scalable, maintainable aur secure kaise banega. Layers (Models → IDEs → Agents) mein sochne se hum clear separation rakhte hain aur future mein koi bhi hissa badalna ya upgrade karna aasaan ho jata hai.

---

### Part B — Practical Task (Screenshot Attached)

**Tool Used:** Google Gemini CLI (gemini-cli latest version)  

**Exact Prompt I gave:**  
```
Write a single, clear, one-paragraph executable specification for an email validation function in TypeScript/Node.js. The function must:
- Check that the email contains exactly one "@"
- Check that there is a valid domain after @ with at least one dot and known TLD (.com, .org, .net, .edu, .io, etc.)
- Return { valid: true, email: normalizedEmail } if valid
- Return { valid: false, error: "clear English message" } with specific helpful errors
```

**Generated Specification (exact output from Gemini CLI):**

```
The validateEmail function accepts a string input and returns an object { valid: boolean, email?: string, error?: string }. It first trims and lowercases the input. It then verifies there is exactly one "@" symbol. If not, it returns { valid: false, error: "Email must contain exactly one @ symbol" }. Next, it splits into local and domain parts; both must be non-empty, otherwise it returns appropriate errors. The domain must contain at least one "." after the @, with non-empty segments and a TLD of 2-6 letters from a whitelist including .com, .net, .org, .edu, .io, .co, .ai, etc. Local part allows letters, numbers, and characters .!#$%&'*+/=?^_`{|}~- but cannot start or end with a dot or have consecutive dots. If all checks pass, it returns { valid: true, email: normalized lowercase email }; otherwise it returns { valid: false } with a clear, specific English error message pointing exactly what failed.
```

(Screenshot of terminal prompt + full output is attached as `practical-task2.png`)

---

### Part C — Multiple Choice Questions

1. B  
2. B  
3. B  
4. B  
5. C  

