# The Desi Celiac: landing page 🌾

A single-file website (`index.html`) for the @thedesiceliac Instagram link-in-bio.

## 1. Turn on the contact form (2 minutes)

Messages are sent by **Web3Forms** (free, 250 messages/month) to thedesiceliac@gmail.com.

1. Go to https://web3forms.com, then click **Create your Access Key**.
2. Enter `thedesiceliac@gmail.com`. They'll email you a key that looks like `a1b2c3d4-....`
3. Open `index.html`, find `YOUR_WEB3FORMS_ACCESS_KEY` and replace it with your key.

Until you add the key, the "Send it" button opens the visitor's email app with the message already filled in, so you won't miss anything.

## 2. Publish on GitHub Pages (free)

1. Create a repository. If you name it `<your-github-username>.github.io`, the site will live at that address.
2. Upload `index.html` (and this README).
3. In the repository, go to **Settings → Pages → Build and deployment**, set **Source: Deploy from a branch**, choose `main` / `(root)` and click **Save**.
4. After about a minute the site is live. Paste the link into your Instagram bio.

## 3. Easy tweaks

- **Your real logo:** save it as `logo.png` next to `index.html`. Then, in the nav, replace `<svg><use href="#badge"/></svg>` with `<img src="logo.png" alt="" width="46" height="46">`.
- **Quiz questions:** edit the `Q = [...]` list in the `<script>` at the bottom.
- **Colours:** change the `:root` variables at the top (`--chili`, `--haldi`, `--navy`…).
