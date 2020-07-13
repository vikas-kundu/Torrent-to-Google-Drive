# Torrent-to-Google-Drive 
Google Collab notebook to store torrent files (large datasets etc) directly to Google Drive. 

#### What is Google Collab?
>Colaboratory, or "Colab" for short, allows you to write and execute Python in your browser, with:
    -Zero configuration required
    -Free access to GPUs
    -Easy sharing
Whether you're a student, a data scientist, or an AI researcher, Colab can make your work easier.

For more info visit [Google Collab](https://colab.research.google.com/notebooks/intro.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vikas-kundu/Torrent-to-Google-Drive/blob/master/torrent_to_google_drive.ipynb)

#### How to use?

- Click the badge which says 'Open in Colab'.
- Goto File > Save a copy in Drive... (a new tab opens with a copy of this notebook).
- Run the whole notebook (Runtime > Run all).
- First, it will ask for an access token to mount Google drive, provide it.
- Thereafter, paste the Magent link of your torrent inside the double quotes at the end of this line of code in the notebook:
>!transmission-cli -f /content/script.sh -w drive/'My Drive'/torrent/ "Enter your Magnet Link or File location here"

After the download finishes the downloaded files will be in there in your drive in a folder named "Torrent".

#### Why to use it?

  - Sometimes datasets can be large and need to be downloaded via torrent. So faster download time and no data charges.
  - Access the dataset or files within multiple projects from Google drive.
  - Faster download time from Google drive instead of a torrent.
  
# This notebook is intended to be used in accordance with the policies of Google collab. The author assumes no responsibility in case of misuse. Please read Google Collab policy before using this notebook [here](https://research.google.com/colaboratory/faq.html).
