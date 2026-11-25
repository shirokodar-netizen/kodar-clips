# Kodar Clips – Privacy Policy

Effective date: November 25, 2026

Kodar Clips ("the app") is a Windows desktop application that helps content creators cut long videos into clips, publish them to their own social media accounts and follow their account metrics. This policy explains what data the app handles.

## 1. Where your data lives
The app runs on your own computer. Videos, projects, settings and metrics are stored locally in your Windows user folder. We do not operate a server that receives your videos, your account data or your metrics.

## 2. Social media accounts (TikTok, YouTube, Instagram)
You may connect your own accounts through the official login of each platform (OAuth). The access tokens are saved only on your computer, encrypted with Windows DPAPI (readable only by your Windows user).

With your permission, the app reads from TikTok:
- **user.info.profile** – avatar, display name, bio, verified status and profile link;
- **user.info.stats** – follower, following, like and video counts;
- **video.list** – your recent public videos (cover, title, views, likes, comments, link).

This information is shown only to you, inside the app's dashboard. A daily snapshot of your counts is stored locally to draw growth charts. It is never sold, shared with third parties or used for advertising.

When you choose to publish a clip, the app sends that video and its caption directly to the platform you selected, using that platform's official API.

## 3. Third-party services
The app talks directly to the official APIs of TikTok, YouTube (Google) and Instagram (Meta), under their own privacy policies. If you configure your own Cloudflare R2 storage, a video may be stored there for a few minutes so Instagram can fetch it, and it is deleted right after.

## 4. License
To validate your license, the app computes an anonymous identifier of your computer (a hash). No personal data is collected for this.

## 5. Your choices
You can disconnect any account at any time in the app's "Contas" (Accounts) menu, which deletes the stored tokens. You can also revoke access in the settings of each platform. Uninstalling the app and deleting the `%APPDATA%\ShiroClips` folder removes all local data.

## 6. Children
The app is not intended for children under 13.

## 7. Contact
Questions about this policy: open an issue at https://github.com/shirokodar-netizen/kodar-clips/issues
