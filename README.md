# Fees Ledger — PWA (phone se hi install)

Ye ek complete PWA hai — koi computer nahi chahiye. Sirf phone browser se
2 minute me apne home screen par install kar sakte ho.

## Step 1: GitHub par account (agar nahi hai)

Phone ke browser (Chrome) me github.com kholo → free account bana lo.

## Step 2: Naya repository banao

1. "+" icon → "New repository"
2. Name do: `fees-ledger`
3. **Public** rakho, "Create repository" dabao

## Step 3: Files upload karo

1. Repo ke andar "Add file" → "Upload files"
2. Is folder ke andar ke saare files/folders select karke upload karo:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icons/` folder (dono PNG files)
3. Neeche "Commit changes" dabao

## Step 4: GitHub Pages on karo

1. Repo ke "Settings" tab me jao
2. Left side me "Pages" pe click karo
3. "Branch" me `main` select karo, folder `/ (root)` rakho → Save
4. 1-2 minute wait karo, ek link milega jaisa:
   `https://tumhara-username.github.io/fees-ledger/`

## Step 5: Phone par install karo

1. Chrome me upar wala link kholo
2. Chrome apne aap "Add to Home screen" ka option dikhayega (ya top-right ⋮ menu → "Add to Home screen")
3. Confirm karo — ab app icon home screen par aa jayega, bilkul normal app jaisa khulega (no browser bar)

Bas ho gaya — ab bina internet ke bhi chalega, data phone me hi save hota hai.

## Note

Agar future me kabhi laptop mil jaye aur Play Store pe daalna ho, wahi React Native version (pehle diya gaya) use kar sakte ho — dono ka design same hai.
