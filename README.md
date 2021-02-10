## Prototype Frontend Backed on Google Colab

This small script is a proof of concept that addresses the need to quickly generate a simple user interface to a machine learning project, supported by a free, yet powerful, computing source, i.e. Google Colab, which offers 16GB GPUs for a couple of hours.

To do so, the script takes advantage of the [Streamlit](https://www.streamlit.io) library for the graphical interface (which is a lot simpler than *Plotly*) and [Ngrok](https://ngrok.com/) for HTTP tunneling - that makes your website available outside of Colab, with a specific URL domain. You can have a free account at Ngrok for this.