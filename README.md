# Proxy Checker

This Python script checks the validity of the proxies by making a request to http://google.com. Valid proxies are saved in an output file.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://user-images.githubusercontent.com/132524328/236690099-d964f319-5418-4f47-9b5f-5bd29fe6a045.png" />
  </a>
</p>


- Python 3.x
- Library `requests` : can be installed by running the command `pip install requests`.

## Utilisation

python3 checker.py <proxy_file> <proxy_type> <output_file> <timeout> 

- `<proxy_file>` : Path of the file containing the proxies to be tested.
- `<proxy_type>` : Type of proxy to search.
- `<output_file>`: Path to the output file for saving valid proxies.
- `<timeout>`: Timeout in milliseconds for each test request.

<p align="center">
  <a href="https://medusa-stealer.cc">
    <img src="https://i.ibb.co/6H8Q2CZ/checkerproxy2.png" />
  </a>
</p>

### Exemple
  
python3 checker.py proxies.txt http valides.txt 5000
  
  
 ### Finally
  
 <p align="center">
  <a href="https://medusa-stealer.cc">
    <img src="https://i.ibb.co/56GmrL5/checkerproxy3.png" />
  </a>
</p>
  

  
 ## Licence

This script is distributed under the MIT license. Please see the [LICENSE](LICENSE) file for more information.
