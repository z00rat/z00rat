<div align="center">
	<br>
	<a href="https://github.com/z00rat/z00rat">
		<img src="README.svg" width="800" height="400" alt="github profile README using svg">
	</a>
	<br>
</div>

---

### Import my gpg key:
```bash
curl -s https://raw.githubusercontent.com/z00rat/z00rat/master/00000586360F8791A5492251129802DDA8074345.public.gpg | gpg --import
```
#### trust and locally sign the imported key if you like
```bash
gpg --edit-key 00000586360F8791A5492251129802DDA8074345 trust quit
gpg --lsign-key 00000586360F8791A5492251129802DDA8074345
```
