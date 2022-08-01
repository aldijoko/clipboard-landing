<script>
</script>

<div class="topContainer">
	<img src="images/logo.svg" alt="" />
	<h1>A history of everything you copy</h1>
	<p>
		Clipboard allows you to track and organize everything you copy. Instantly access your clipboard
		on all your devices.
	</p>
	<div class="btnDownload">
		<button class="btnIos">Download for IOS</button>
		<button class="btnMac">Download for Mac</button>
	</div>
</div>

<div class="oneContainer">
	<h1 class="oneHeader">Keep track of your snippets</h1>
	<p class="oneSubtitle">
		Clipboard instantly stores any item you copy in the cloud, meaning you can access your snippets
		immediately on all your devices. Our Mac and iOS apps will help you organize everything.
	</p>
	<div class="oneContent">
		<div class="oneImg">
			<img class="imgBg" src="images/image-computer.png" alt="" />
		</div>
		<div class="oneTxt">
			<div class="oneFeature">
				<h1 class="featureHeader">Quick Search</h1>
				<p class="featureSubtitle">
					Easily search your snippets by content, category, web address, application, and more.
				</p>
			</div>
			<div class="oneFeature">
				<h1 class="featureHeader">iCloud Sync</h1>
				<p class="featureSubtitle">Instantly saves and syncs snippets across all your devices.</p>
			</div>
			<div class="oneFeature">
				<h1 class="featureHeader">Complete History</h1>
				<p class="featureSubtitle">
					Retrieve any snippets from the first moment you started using the app.
				</p>
			</div>
		</div>
	</div>
</div>

<div class="twoContainer">
	<h1 class="twoHeader">Access Clipboard anywhere</h1>
	<p class="twoSubtitle">
		Whether you’re on the go, or at your computer, you can access all your Clipboard snippets in a
		few simple clicks.
	</p>
	<div class="twoImg">
		<img class="imgDevice" src="images/image-devices.png" alt="" />
	</div>
</div>

<div class="threeContainer">
	<h1 class="threeHeader">Supercharge your workflow</h1>
	<p class="threeSubtitle">We’ve got the tools to boost your productivity.</p>
	<div class="threeContent">
		<div class="tools">
			<img src="images/icon-blacklist.svg" alt="" />
			<h1 class="headerTools">Create blacklists</h1>
			<p class="subtitleTools">
				Ensure sensitive information never makes its way to your clipboard by excluding certain
				sources.
			</p>
		</div>
		<div class="tools">
			<img src="images/icon-text.svg" alt="" />
			<h1 class="headerTools">Plain text snippets</h1>
			<p class="subtitleTools">
				Remove unwanted formatting from copied text for a consistent look.
			</p>
		</div>
		<div class="tools">
			<img src="images/icon-preview.svg" alt="" />
			<h1 class="headerTools">Sneak preview</h1>
			<p class="subtitleTools">Quick preview of all snippets on your Clipboard for easy access.</p>
		</div>
	</div>
	<div class="threeLogo">
		<div class="threeImg">
			<img class="threeImgBg" src="images/logo-google.png" alt="" />
		</div>
		<div class="threeImg">
			<img class="threeImgBg" src="images/logo-ibm.png" alt="" />
		</div>
		<div class="threeImg">
			<img class="threeImgBg" src="images/logo-microsoft.png" alt="" />
		</div>
		<div class="threeImg">
			<img class="threeImgBg" src="images/logo-hp.png" alt="" />
		</div>
		<div class="threeImg">
			<img class="threeImgBg" src="images/logo-vector-graphics.png" alt="" />
		</div>
	</div>
</div>

<div class="bottomContainer">
	<h1 class="fourHeader">Clipboard for iOS and Mac OS</h1>
	<p class="fourSubtitle">
		Available for free on the App Store. Download for Mac or iOS, sync with iCloud and you’re ready
		to start adding to your clipboard.
	</p>
    <div class="btnDownload">
		<button class="btnIos">Download for IOS</button>
		<button class="btnMac">Download for Mac</button>
	</div>
</div>

<footer>
    <div class="footerContainer">
        <div class="footerContent">
            <div class="footerLogo">
                <img class="footerImg" src="images/logo.svg" alt="">
            </div>
            <div class="footerMenu">
                <div class="menuList">
                    <ul>
                        <li>FAQs</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div class="menuList">
                    <ul>
                        <li>Privacy Policy</li>
                        <li>Press Kit</li>
                    </ul>
                </div>
                <div class="menuList">
                    <ul>
                        <li>Install Guide</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="sosmed">
            <span><i class="fab fa-facebook" /></span>
            <span><i class="fab fa-twitter" /></span>
            <span><i class="fab fa-instagram" /></span>
        </div>
    </div>

</footer>

<style>
	.topContainer, .bottomContainer {
		width: 100%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 100px 50px;
	}

	.topContainer h1 {
		margin-top: 60px;
		letter-spacing: 2px;
	}

	.topContainer p {
		margin-top: 10px;
		width: 55%;
		padding: 0px 80px;
		text-align: center;
	}

	.btnDownload {
		width: 30%;
		margin-top: 40px;
		display: flex;
		justify-content: center;
		align-items: center;
		gap: 10px;
	}

	.btnIos {
		background-color: var(--Strongcyan);
		color: white;
		border: 1px solid var(--Strongcyan);
		border-radius: 20px;
		padding: 15px;
		width: 50%;
		cursor: pointer;
		box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
        font-weight: 600;
	}

    .btnIos:hover {
        background-color: hsl(171, 60%, 72%);
        border: 1px solid hsl(171, 60%, 72%);
    }

	.btnMac {
		background-color: var(--lightBlue);
		color: white;
		border: 1px solid var(--lightBlue);
		border-radius: 20px;
		padding: 15px;
		width: 50%;
		cursor: pointer;
		box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
        font-weight: 600;
	}

    .btnMac:hover {
        background-color: hsl(233, 84%, 78%);
        border: 1px solid hsl(233, 84%, 78%);
    }

	.oneContainer,
	.twoContainer {
		width: 100%;
		/* display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center; */
		padding: 100px 50px;
	}

	.oneHeader,
	.twoHeader,
	.threeHeader,
    .fourHeader {
		width: 100%;
		text-align: center;
	}

	.oneSubtitle,
	.twoSubtitle,
	.threeSubtitle,
    .fourSubtitle {
		margin-top: 20px;
		width: 100%;
		padding: 0px 350px;
		text-align: center;
	}

	.oneContent {
		width: 100%;
		display: flex;
		margin-top: 80px;
	}

	.oneImg {
		width: 50%;
	}

	.imgBg {
		width: 100%;
	}

	.oneTxt {
		width: 50%;
		/* padding: 0px 80px; */
	}

	.oneFeature {
		width: 100%;
		/* margin-top: 40px; */
		padding: 30px 100px;
	}

	.featureHeader {
		font-size: 24px;
		width: 100%;
		/* margin-left: 80px; */
	}

	.featureSubtitle {
		/* text-align: left; */
		margin-top: 10px;
		width: 75%;
	}

	.twoImg {
		width: 100%;
		margin-top: 50px;
		display: flex;
		justify-content: center;
	}

	.threeContainer {
		width: 100%;
		text-align: center;
	}

	.threeContent {
		display: flex;
		width: 100%;
		justify-content: space-between;
		margin-top: 50px;
	}

	.tools {
		flex: 0 0 32%;
		padding: 50px 0px;
	}

	.headerTools {
		font-size: 24px;
		font-weight: 400;
		padding: 20px 0px;
	}

	.subtitleTools {
		padding: 0px 50px;
		text-align: center;
	}

	.threeLogo {
		display: flex;
		width: 100%;
		justify-content: space-between;
	}

	.threeImg {
		width: 100%;
		padding: 50px;
	}

	.threeImgBg {
		width: 90%;
		padding: 150px 0px;
	}

    .footerContainer {
        background-color: var(--Grayish);
        padding: 30px;
        display: flex;
        /* justify-content: space-between; */
        align-items: center;
        width: 100%;
    }

    .footerContent {
        display: flex;
        width: 50%;
        align-items: center;
    }

    .footerLogo {
        width: 20%;
    }

    .footerImg {
        width: 40%;
    }

    .footerMenu {
        width: 80%;
        display: flex;
        /* flex: 1; */
        /* justify-content: space-between; */
    }

    .menuList {
        width: 100%;
    }
    .menuList li {
        color: var(--darkGrayish);
        list-style: none;
        margin-top: 20px;
        cursor: pointer;
    }

    .menuList li:hover {
        color: var(--Strongcyan);
    }

    .sosmed {
		/* margin-top: 30px; */
        width: 50%;
        display: flex;
        justify-content: flex-end;

	}

    .sosmed span i {
		height: 75px;
		width: 75px;
		color: var(--darkGrayish);
		cursor: pointer;
		padding: 50px 0;
	}

    .sosmed span i:hover{
        color: var(--Strongcyan);
    }

</style>
