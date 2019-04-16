# Plugin requirements #
This plugin has primarily been tested with Eclipse 3.3 and 3.4 It should work with 3.x releases, but let us know if you have any problems. The plugin is not compatible with versions of Eclipse preceding 3.3. The plugin runs under Java 1.5/5.0, or newer.

# Plugin installation #
If you have previously installed a version of the FindBugs plugin prior to mid-May, 2006, then you should remove it first. Simply remove the de.tobject.findbugs_0.0.n directory from Eclipse's plugins directory.

To install the FindBugs plugin:

1. In Eclipse, click on Help -> Software Update -> Find and Install...
2. Choose the Search for new features to install option, and click Next.
3. Click New Remote Site.
4. Enter the following:
   - **Name:**FindBugs update site
   - **URL:** one of the following (note: no final slash on the url)
       - **http://findbugs.cs.umd.edu/eclipse for official releases**
       - **http://findbugs.cs.umd.edu/eclipse-candidate for candidate releases and official releases**
       - **http://findbugs.cs.umd.edu/eclipse-daily for all releases, including developmental ones**
and click **OK**.
5. "FindBugs update site" should appear under Sites to include in search. 
Click the checkbox next to it to select it, and click Finish.
6. You should see **FindBugs Feature** under **Select features to install**. 
(You may have to click on one or two triangles to make it visible in the tree.)
7. Select the checkbox next to it and click next.
Select the **I accept** option to accept the license and click **Next**.
8. Make sure the location is correct where you're installing it. The default (your workspace) should be fine. Click **Finish**.
9. The plugin is not digitally signed. Go ahead and install it anyway.
10. Click **Yes** to make Eclipse restart itself.