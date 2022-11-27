## WARNING

This is an older version of the book Streamlit for Data Science. I would recommend that you move over to [this repo](https://github.com/tylerjrichards/Streamlit-for-Data-Science) for the updated book. If you would rather work off the older repository, I kept the older repo here for you all to use! If you own the older version of the book, and want the newer one, I am happy to send you a pdf so you do not have to purchase the book twice. No sense in that! Just reach out to me via [Twitter](https://www.twitter.com/tylerjrichards) and DM me.


### Getting Started with Streamlit for Data Science
Welcome to [Getting Started with Streamlit for Data Science!](https://www.amazon.com/gp/product/180056550X) I'm the author, [Tyler Richards](www.tylerjrichards.com), and I wrote this book when I was at Facebook, and have since moved to work for Streamlit.
If you're coming here from the book, go ahead and take a peak inside each one of the sub-folders in this main repo. You can feel free to [clone this repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository), and if anything doesn't work you can always [open an issue or pull request](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request) or just find me on [Twitter](https://www.twitter.com/tylerjrichards) and DM me until I figure it out.
If you're coming here from another place on the internet, feel free to use these respositories and examples however you would like! They are more useful in context, and so I would obviously recommend [giving the book a shot](https://www.amazon.com/Getting-Started-Streamlit-Data-Science-ebook/dp/B095Z1R3BP). If you're a young data scientist who can't afford the book, please reach out to me and I'd be happy to provide a copy no questions asked.
The first chapter starts in the folder 'clt_app', head over there with the book in hand and enjoy!

#### Book Edits
Streamlit is an ever-changing library, and by the time this book was written it was already slightly behind compared to newer versions of the library. If you notice error messages, please message me about them so I can get them all fixed or note them below!
1. st.beta_columns is out of beta!
As of now, st.beta_columns is now called simply st.columns! Excited to see this one out of beta, and depending on your Streamlit version you will get an error if you use st.beta_columns
2. There is an open bug caused when you redirect the output of 'streamlit config show' to the config.toml file for your project, I would instead copy and paste this manually! See [this post](https://discuss.streamlit.io/t/cant-run-streamlit-if-i-create-config-toml/22004/5) for more info
3. There is a closed issue where the Random Forest Classifier does not have feature names, which throws a warning for sklearn >= 1.0. The issue is [here](https://github.com/tylerjrichards/Getting-Started-with-Streamlit-for-Data-Science/issues/5#issuecomment-1100659506). You can ignore this warning, or (as [pythonic2020](https://github.com/pythonic2020) kindly pointed out in the issue) "converting X_train dataframe to np array (X_train.values) before fitting removes the warning").
