## d3dshot install error

fixed by downloading the source code from https://github.com/SerpentAI/D3DShot 

opening pyproject.toml and replacing:
    
   pillow = "~7.1.2" with   
    
    pillow = ">=7.1.2"

install with:
  
    pip install ./D3DShot-0.1.5
