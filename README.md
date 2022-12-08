# RuDok
RuDok-Application for managing and creating documents
<br/>Project for Software Design course
<br/>Jawa Swing desktop application built using various design patterns:
<ul>
  <li>Composite</li>
  <li>Observer</li>
  <li>State</li>
  <li>Command</li>
  <li>Factory</li>
  <li>Singletone</li>
</ul>

This application was inspired by PowerPoint, software for presentation design.
RuDok allows you to create multiple projects inside your workspace and multiple presentations inside created projects.
You can design your own presentation slides by adding slots. Slots can be either text or images.

Content inside the text slot can be edited and stylized by adding text styles:
<ul>
  <li>Bold</li>
  <li>Italic</li>
  <li>Underline</li>
</ul>

![slot](https://user-images.githubusercontent.com/74270528/206568558-e587b780-a294-4643-981e-85fa5cb96723.PNG)

Slots can be moved around the slide and also they can be deleted. RuDok supports 2 work modes, editing mode and presentation mode. Sharing created presentations between projects is also possible.

You can also save your presentations and projects and open them later, this is achieved using serialization in java.
