ciemailinlie
============

Codeigniter email class with inline attachments

How to use
============

- If you want to display an image inline, it must be attached (simple enough using email->attach($file))
- Like with everything, no email service was created equal…even though we have RFCs (see my screen shots of hotmail, gmail, and yahoo. Note that yahoo violates, imo, the unspoken rule of auto-loading attached images but yet not auto-loading non-attached images)
- To reference an attached image in your HTML page, use cid:filename.ext, note the cid:

Disclaimer
============

Yes, I know this should extend the CI email class instead of overwriting it. Please don't complain about that. I personally don't use codeigniter any more (for a couple of reasons - namely I've made my own, and codeigniter is no longer being supported). If you want to fix it to extend the CI_Email class - it would be better if you forked this repo versus a pull request.
This was made as a quick feature integration to a site which had a CI version that would really never change.

I release this to the world in the hopes that it would be helpful to someone.

You can find the original post here: http://ellislab.com/forums/viewthread/144855/
Mirror: http://i.imgur.com/AWNrq0q.png