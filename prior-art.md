# Prior Art

## Metadata Files

### OSSMETADATA

Developed and used by Netflix to initially power their internal project dashboards.

**Example:** <https://github.com/Netflix/edda/blob/master/OSSMETADATA>

### .google/packaging.yaml

Developed and used by Google to document and package sample projects.  One
primary use of this data is to power the sample project directory inside of
[Android Studio](https://developer.android.com/studio/).

**Example:** <https://github.com/googlesamples/android-StorageProvider/blob/master/.google/packaging.yaml>

### about_yaml

Developed at [18F](https://18f.gsa.gov) initially for their own projects.
Documented as powering the [18F Dashboard](https://18f.gsa.gov/dashboard)
(though no longer appears to be active).

**Docs:** <http://www.rubydoc.info/gems/about_yml/0.0.10>  
**Example:** <https://github.com/18F/about_yml/blob/master/.about.yml>

### .ABOUT files, ABC Data
​
Simple convention with metadata YAML files stored side-by-side with code
they document.(Note: these predate the 18F about_yaml)
​
Used by AboutCode.org, libraries.io and other:
 **Docs:** https://github.com/nexB/aboutcode/tree/master/aboutcode-data
 **Example:**
 - https://github.com/nexB/scancode-toolkit/tree/develop/thirdparty/prod
 - https://libraries.io/npm/jquery/3.2.1.about 
 - https://github.com/triplecheck/components/tree/master/samples


## Schemas

Various schemas have been developed to describe software projects:

 - https://schema.org/SoftwareApplication
 - https://github.com/CodeMeta/codemeta
 - https://github.com/ewilderj/doap

## README Badges

One common ad hoc way of expressing some of this metadata is through badges
embedded in README files.  These badges have the advantage of being very
visibile, and therefore more likely to stay up to date.  However, they are not
as easily machine parseable for use in other applications.  A few of these
projects that document types of metadata we may be interested in:

 - <https://github.com/orangemug/stability-badges>
 - <https://github.com/insin/caveat-utilitor>
 - <https://github.com/danielbachhuber/statemarks>

