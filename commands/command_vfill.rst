vfill
=====

Brief Description
-----------------


\vspace{\fill} and \vfill are not exactly equivalent. They are if they appear between paragraphs, but not if they appear in a paragraph.

\vspace{\fill} in a paragraph will add the filling vertical space below the line in which it eventually appears;

\vfill ends the paragraph at the spot and adds the filling vertical space.

Indeed \vfill is a TeX primitive, while \vspace is defined by LaTeX to have the described effect when found in a paragraph. In vertical mode, \vspace{<glue>} is equivalent to the primitive \vskip<glue>. See \vspace vs. \vskip for more information.

There is no \vfill*, if you're asking about this. The difference between \vspace{<glue>} and \vspace*{<glue>} is that the latter is not discarded at page breaks. See Question about spacing \hspace and \vspace.

https://tex.stackexchange.com/questions/118802/what-is-the-difference-between-vspace-fill-and-vfill