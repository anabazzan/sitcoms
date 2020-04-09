# sitcoms

This repository contains datasets regarding plain text descriptions of graphs that represent episodes of the 3 TV shows:  "Seinfeld", "How I Met Your Mother", and "The Big Bang Theory". 
These datasets were manually generated and curated by Prof. Ana Bazzan (www.inf.ufrgs.br/ ~bazzan). 
If you use this dataset please acknowledge the source (this repository) and/or the following publication: 
https://seer.ufrgs.br/rita/issue/archive (vol. 27 nb. 2)
The dataset regarding the data about the show "Friends" is located somewhere else:
https://github.com/anabazzan/friends/blob/master/friends_episodes.txt

It can be used as input files to software that process graphs such as igraph. However, the current dataset has lines that are to be interpreted as comments as, e.g., lines that mark the beginning of a given episode; also, some lines include comments regarding specific types of episodes. To use this dataset in igraph, you need to parse using regular expressions.

A note about license: THE DATASE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATASET OR THE USE OR OTHER DEALINGS IN THE DATASET.
