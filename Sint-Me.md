# SintMe Write-Up

## Challenge Description
Participants are given an image featuring:
1. A koel bird on the right.
2. The KIIT logo on the bottom left.
3. The Google logo with 5 stars on the top left.

### Author
darkzeus

## Write-Up

1. **Initial Interpretation:**
   - The image hints at Google Maps and points to **KIIT Koel Campus - Campus 1** based on the bird (koel) and the KIIT logo.

2. **Google Maps Search:**
   - Searching "Koel Campus" on Google Maps reveals a review stating: **"Koels be finding koels now."**
   - The attached photo in the review shows two irregularities:
     - Elon Musk's photo replaces the KIIT Place name on a board.
     - A username, `koel_the_bird`, replaces the KIIT logo on another board.

3. **Follow the Username:**
   - The username hints to **X.com (formerly Twitter)**.
   - Visiting `x.com/koel_the_bird` leads to an account named **"you found the koel"** with one post:
     - "koels hello"
     - The post contains a photo of a QR code.

4. **Decrypting the QR Code:**
   - Decrypting the QR code reveals a **text-based key**.
   - This key serves as the password to the linked MEGA folder: `https://mega.nz/file/ci01Ua4K`.

5. **MEGA Folder Access:**
   - Using the QR code password grants access to the folder.
   - Inside, a photo can be downloaded.

6. **Analyzing the Photo:**
   - The photo is of the entrance to **Kalinga Institute of Dental Sciences (KIDS)**.
   - The top name board reads **Kalinga Institute of Dental Science**. Upon close inspection, the Odia part of the board translates to: **"Check the strings."**

7. **Extracting the Flag:**
   - Running `strings omg.jpg` in the terminal reveals the last entry:
     - **`k0e1_t7e_b1rD`**

---

## Final Flag
`iotctf{k0e1_t7e_b1rD}`

