# gai-project4
dip.ipynb:單獨的dip模型
ddpm.ipynb:單獨ddpm模型
ddipm.ipynb:兩者合成的模型
evaluate.ipynb:將最後的結果進行評估，使用psnr以及ssim
以上均在colab上運行
正式運作方式為分別跑完ddpm及ddipm兩個之後，程式碼會自動儲存檔案，接著再把兩個檔案的路徑輸入到evaluate.ipynb裡面的image1和image2部分就能算出分數
