# rul
A concept idea of a url shortener with no database

## Idea
Building scalable url shorteners requires large databases. When those go down, they indirectly take down all the links they are serving to their clients. What if there was a way to effectivley "compress" urls without depending on a private database to hold the full path.

## Proof of concept
The goal of this project is to create a proof of concept using shared compression dictionnaries. This method has shortcomings as running compression on long urls with high entropy is unlikely to produce much shorter results. Even though this type of url is typically what url shorteners are aimed to eliminate.
