<br>

<img src="https://user-images.githubusercontent.com/7164864/217935870-c0bc60a3-6fc0-4047-b011-7b4c59488c91.png" alt="Streamlit logo" style="margin-top:50px"></img>

# Bootcamp21 was here. 👋

**A faster way to build and share data apps.**

Streamlit lets you turn data scripts into shareable web apps in minutes, not weeks. It’s all Python, open-source, and free! And once you’ve created an app you can use our [Community Cloud platform](https://streamlit.io/cloud) to deploy, manage, and share your app.


## Installation

Open a terminal and run:

```bash
$ pip install streamlit
$ streamlit hello
```

If this opens our sweet _Streamlit Hello_ app in your browser, you're all set! If not, head over to [our docs](https://docs.streamlit.io/library/get-started) for specific installs.

The app features a bunch of examples of what you can do with Streamlit. Jump to the [quickstart](#quickstart) section to understand how that all works.

<img src="https://user-images.githubusercontent.com/7164864/217936487-1017784e-68ec-4e0d-a7f6-6b97525ddf88.gif" alt="Streamlit Hello" width=500 href="none"></img>

## Quickstart

### A little example

Create a new file `streamlit_app.py` with the following code:
```python
import streamlit as st
x = st.slider("Select a value")
st.write(x, "squared is", x * x)
```

Now run it to open the app!
```
$ streamlit run streamlit_app.py
```

<img src="https://user-images.githubusercontent.com/7164864/215172915-cf087c56-e7ae-449a-83a4-b5fa0328d954.gif" width=300 alt="Little example"></img>

### Give me more!

Streamlit comes in with [a ton of additional powerful elements](https://docs.streamlit.io/library/api-reference) to spice up your data apps and delight your viewers. Some examples:


<table border="0">
   <tr>
     <td><img src="https://user-images.githubusercontent.com/7164864/217936099-12c16f8c-7fe4-44b1-889a-1ac9ee6a1b44.png" style="max-height:150; width:auto; display:block;"></td>
     <td><img src="https://user-images.githubusercontent.com/7164864/215110064-5eb4e294-8f30-4933-9563-0275230e52b5.gif"  style="max-height:150; width:auto; display:block;"></td>
     <td><img src="https://user-images.githubusercontent.com/7164864/215174472-bca8a0d7-cf4b-4268-9c3b-8c03dad50bcd.gif" style="max-height:150; width:auto; display:block;"></td>
     <td><img src="https://user-images.githubusercontent.com/7164864/217936149-a35c35be-0d96-4c63-8c6a-1c4b52aa8f60.png" style="max-height:150; width:auto; display:block;"></td>
     <td><img src="https://user-images.githubusercontent.com/7164864/215173883-eae0de69-7c1d-4d78-97d0-3bc1ab865e5b.gif" style="max-height:150; width:auto; display:block;"></td>
     <td><img src="https://user-images.githubusercontent.com/7164864/215109229-6ae9111f-e5c1-4f0b-b3a2-87a79268ccc9.gif" style="max-height:150; width:auto; display:block;"></td>

  </tr>
    <tr>
      <td>Input widgets</td>
      <td>Dataframes</td>
      <td>Charts</td>
      <td>Layout</td>
      <td>Multi-page apps</td>
      <td>Fun</td>
   </tr>
<table>

Our vibrant creators community also extends Streamlit capabilities using  🧩 [Streamlit Components](http://components.streamlit.app).

## Get inspired

There's so much you can build with Streamlit:
- 🧬  [Science & technology apps](https://streamlit.io/gallery?category=science-technology)
- 💬  [NLP & language apps](https://streamlit.io/gallery?category=nlp-language)
- 👀  [Computer vision apps](https://streamlit.io/gallery?category=computer-vision-images)
- 🏦  [Finance & business apps](https://streamlit.io/gallery?category=finance-business)
- 🗺  [Geography & society apps](https://streamlit.io/gallery?category=geography-society)
- and more!

**Check out [our gallery!](https://streamlit.io/gallery)** 🎈

## Community Cloud

Deploy, manage and share your apps for free using our [Community Cloud](https://streamlit.io/cloud)! Sign-up [here](https://share.streamlit.io/signup). <br><br>
<img src="https://user-images.githubusercontent.com/7164864/214965336-64500db3-0d79-4a20-8052-2dda883902d2.gif" width="400"></img>

## Resources

- Streamlit [docs](https://docs.streamlit.io), [community forum](https://discuss.streamlit.io) and [blog](https://blog.streamlit.io).
- Extend Streamlit's capabilities by installing or creating your own [Streamlit Components](http://components.streamlit.app/).
- Help others find and play with your app by using the Streamlit GitHub badge in your repository:
```markdown
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](URL_TO_YOUR_APP)
```
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/streamlit/roadmap)

## License

Streamlit is completely free and open-source and licensed under the [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) license.
