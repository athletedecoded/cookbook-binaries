# Sample Binaries

## CPU
* Quantized
* Falcon

## CUDA
* Falcon
* Phi

## cuDNN
* Falcon
* Phi

<hr>

## Git Large File Storage Configuration

```
# per https://github.com/git-lfs/git-lfs#getting-started

curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs
git lfs track "binaries/cpu/*"
git lfs track "binaries/cuda/*"
git lfs track "binaries/cudnn/*"
```

