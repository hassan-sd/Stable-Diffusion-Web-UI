<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/AUTOMATIC1111/stable-diffusion-webui">Stable Diffusion Web UI</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/Stable-Diffusion-Web-Ui/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/Stable-Diffusion-Web-Ui?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/Stable-Diffusion-Web-Ui/issues"><img src="https://img.shields.io/github/issues/catppuccin/Stable-Diffusion-Web-Ui?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/Stable-Diffusion-Web-Ui/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/Stable-Diffusion-Web-Ui?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/Stable-Diffusion-Web-Ui/main/assets/res.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/Stable-Diffusion-Web-Ui/main/assets/latte.png"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/Stable-Diffusion-Web-Ui/main/assets/frappe.png"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/Stable-Diffusion-Web-Ui/main/assets/macchiato.png"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/Stable-Diffusion-Web-Ui/main/assets/mocha.png"/>
</details>

## Usage

1. Clone this repository locally
2. Create the file `user.css` in your stable-diffusion-webui directory
3. Copy the contents of the desired flavor into `user.css`
4. Restart the Web UI

## 🙋 FAQ

-	Q: **_"How do I change the accent color?"_**\
	A: Open `user.css` and set the variavble `--accent: var(--{preferred color});`
	
-	Q: **_"The theme isn't being applied???"_**\
	A: Sometimes Web UI doesn't automatically figure out your preferred theme. Try adding `/?__theme=dark` to the url and see if the theme is applied. Below are the steps to make this change persistent on different systems:
	- **Linux / MacOS**: Edit `webui-user.sh` and uncomment and set this variable as `export COMMANDLINE_ARGS="--theme=dark $COMMANDLINE_ARGS"`
	- **Windows**: Edit `webui-user.bat` and set this variable by `set COMMANDLINE_ARGS=--theme=dark`. 
	
	If you are still having trouble then consult the relevant part of the [webui wiki](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Features#usercss). 
	
-	Q: **_"Why doesn't the theme look like the previews?"_**\
	A: The main UI is constantly being changed upstream, so our previews may not match what the theme will look like for you. Though the previews may be behind, we are frequently updating the themes whenever there is a change in the Web UI repo. Though if you notice a style issue with a recent version of webui, feel free to open an issue on this repo.    
	
-	Q: **_"Why isn't {extension} themed?"_**\
	A: Some extensions use their own style sheets that don't play nice with `user.css`.

## 💝 Thanks to

- [Kettukaa](https://github.com/Kettukaa)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
