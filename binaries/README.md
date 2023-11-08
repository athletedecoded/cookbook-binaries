# Sample Binaries

```
# Download
wget -O <model-target> https://github.com/athletedecoded/cookbook-binaries/raw/main/binaries/<target>/<model>?download=
# Ex.
wget -O quantized-cpu https://github.com/athletedecoded/cookbook-binaries/raw/main/binaries/cpu/quantized?download=
# Run
./quantized-cpu --prompt "how long is a piece of string"
```

## CPU
* [Blip](./cpu/blip)
* [Falcon](./cpu/falcon)
* [Mistral](./cpu/mistral)
* [Phi](./cpu/phi)
* [Quantized](./cpu/quantized)
* [Whisper](./cpu/whisper)

## CUDA
* [Blip](./cuda/blip)
* [Falcon](./cuda/falcon)
* [Mistral](./cuda/mistral)
* [Phi](./cuda/phi)
* [Stable Diffusion](./cuda/stable-diffusion)
* [Whisper](./cuda/whisper)

## cuDNN
* [Blip](./cudnn/blip)
* [Falcon](./cudnn/falcon)
* [Mistral](./cudnn/mistral)
* [Phi](./cudnn/phi)
* [Stable Diffusion](./cudnn/stable-diffusion)
* [Whisper](./cudnn/whisper)

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

