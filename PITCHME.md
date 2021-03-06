---?image=/assets/image/black.jpg&opacity=90

### Welcome to the Demo presentation!

[UniBit Labs](http://universalbitproject.com)

##### Presentation covering UI/UX changes to UniBit applications. 

---?image=/assets/image/black.jpg&opacity=75

### Encryption App Video Demo

![YouTube Video](https://www.youtube.com/embed/Sd2oKioNqQU)


---?image=/assets/image/black.jpg&opacity=75

### Encryption App
<center>
Current UI<br>

![alt](/assets/image/demo/cryptit-main.jpg)<br>
<br>
Demo: https://securedoc.io 
</center>

---?image=/assets/image/black.jpg&opacity=75

### Encryption App Modified
<center>
Proposed Changes
<br>
![alt](assets/image/encryption-app-mod.jpg)
<br>
Website: https://encryption.app 
</center>

---

### Encryption App Tech. Code Block
'''javascript
// Encrypt the file!

			reader.onload = function(e){

				// Use the CryptoJS library and the AES cypher to encrypt the 
				// contents of the file, held in e.target.result, with the password

				var encrypted = CryptoJS.AES.encrypt(e.target.result, password);

				// The download attribute will cause the contents of the href
				// attribute to be downloaded when clicked. The download attribute
				// also holds the name of the file that is offered for download.

				a.attr('href', 'data:application/octet-stream,' + encrypted);
				a.attr('download', file.name + '.encrypted');

				step(4);
			};

			// This will encode the contents of the file into a data-uri.
			// It will trigger the onload handler above, with the result

			reader.readAsDataURL(file);
		}
		else {

			// Decrypt it!

			reader.onload = function(e){

				var decrypted = CryptoJS.AES.decrypt(e.target.result, password)
										.toString(CryptoJS.enc.Latin1);

				if(!/^data:/.test(decrypted)){
					alert("Invalid pass phrase or file! Please try again.");
					return false;
				}

				a.attr('href', decrypted);
				a.attr('download', file.name.replace('.encrypted',''));

				step(4);
			};

			reader.readAsText(file);
		}
	});
'''


---?image=/assets/image/black.jpg&opacity=90

### Vote App

![YouTube Video](https://www.youtube.com/embed/-VXYZmrquYA)

![alt](/assets/image/winner-sxsw.png)

---?image=/assets/image/black.jpg&opacity=75

### Vote App 
<center>
Current User Interface
<br>
![alt](/assets/image/demo/voteapp-main.png)
<br>
Website: http://vote.rockthepoll.com
</center>

---?image=/assets/image/black.jpg&opacity=75

### Vote App Modified

![alt]()
<br>
Results website: http://198.23.196.54:2750/VoteChain/assetref/7-264-40763#holders

---?image=/assets/image/black.jpg&opacity=90

### Universal Basic Income Tokens

![YouTube Video](https://www.youtube.com/embed/QCZNvs_f6VI)

---?image=/assets/image/black.jpg&opacity=75

### UBIT 

<center>
Current User Interface
 <br>
![alt](/assets/image/ubit-main.png)
<br></center>

Website: https://ubit.chickenkiller.com

---?image=/assets/image/black.jpg&opacity=75

### UBIT Modified

<div class="left">
     Current UI
    <img src="https://github.com/UniBitProject/team-demo/blob/master/assets/image/ubit-original.png?raw=true"></img>
</div>
<div class="right">
  New UI
  <img src="https://github.com/UniBitProject/team-demo/blob/master/assets/image/ubit-new2.png?raw=true"></img>
</div>

---?image=/assets/image/black.jpg&opacity=90

### Universal Multichain Wallet

![YouTube Video](https://www.youtube.com/embed/hbozav9dvV0)


---?image=/assets/image/black.jpg&opacity=75

### UMW App
Current UI
<br>
![alt](/assets/image/demo/umw-main.png)
<br>
Website: http://unibit.rundis.com 

---?image=/assets/image/black.jpg&opacity=75

### UMW App Modified

![alt](https://raw.githubusercontent.com/UniBitProject/team-demo/master/assets/image/nebula.png)

---?image=/assets/image/black.jpg&opacity=90

### The Scout Browser

![YouTube Video](https://www.youtube.com/embed/dNJdJIwCF_Y)

---?image=/assets/image/black.jpg&opacity=75

### Scout Browser App
Current UI
<br>
![alt](/assets/image/demo/scoutbrowser-main.png)
<br>
Website: http://scout.click 

---?image=/assets/image/black.jpg&opacity=75

### Scout Browser App Modified

![alt](assets/image/encryption-app-mod.jpg)

- UI changes

---?image=/assets/image/black.jpg&opacity=90

### UniqueSwarm Script

![YouTube Video](https://www.youtube.com/embed/HaM_SzCkfpw)

---?image=/assets/image/black.jpg&opacity=75

### Unique Swarm

![alt](/assets/image/demo/)

- Status: In Progress 

---?image=/assets/image/black.jpg&opacity=75

### Unique Swarm Modified

![alt]()

---?image=/assets/image/black.jpg&opacity=75

### PC New

Video Demo

---?image=/assets/image/black.jpg&opacity=75

### PC New App

![alt](/assets/image/pc-new-1.png)

---?image=/assets/image/black.jpg&opacity=75

### PC New App Modified

![alt](/assets/image/pc-new-3.png)
 
---?image=/assets/image/black.jpg&opacity=90

### The UniBit Framework

Community Discussion Takes Place Here
for all things App #8 related.

---?image=/assets/image/black.jpg&opacity=75


### UniBit Framework

Current UI
<br>
![alt](/assets/image/fw-white.png)
<br>
Website: http://

---?image=/assets/image/black.jpg&opacity=75

### UniBit Framework Modified

![alt](/assets/image/fw-dark.png)
 
- Future website: https://unibit.app

---?image=/assets/image/black.jpg&opacity=75

### The Trucking App


---?image=/assets/image/black.jpg&opacity=75

### Trucking App

![alt](/assets/image/trucking-app-gps.png)

- Current main screen 
- Current website: http://

---?image=/assets/image/black.jpg&opacity=75

### Trucking App Modified

![alt](/assets/image/truck-app-main.png)

- Proposed changes 
- Future website: http://

---?image=/assets/image/black.jpg&opacity=75

### Upcoming Changes

- Matching Color Scheme Across All Products/Services? |
- Open Source? Proprietary? |
- Custom 3D/Animated Styling |
- Custom Logo, TOC, and Footnotes |

---?image=/assets/image/black.jpg&opacity=90

### How to get Involved!

![alt](/assets/image/unnamed.png)

<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details hidden here.</a>
</div>
<div class="right">
    <ul>
        <li>Bug Bounties</li>
        <li>Graphics Art Bounties</li>
        <li>Spread the word!</li>
        <li>Use our apps!</li>
        <li>Leave feedback to make things better!</li>
    </ul>
</div>


---?image=assets/image/gitpitch-audience.jpg&opacity=100

@title[Download!]

### <span class="purple">Get started!</span>
### [Suggest Changes Here @fa[fas fa-edit]](https://gitpitch.com/template/download/white)

