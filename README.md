# codestyle
My customized code style which is built on linkedin code style.

# Apply on Intellij
- Install `Eclipse code formatter` plugin.
- Open `settings`
- Choose `other settings`, `Eclipse code foramtter`
- Import `codestyle.xml`
- Uncheck `Optimize Imports`
- Navigate to `Editor` -> `Code Style` -> `Java` and then to `Imports` tab
- Modify `Class count to use import with '*':` to `99`
- Modify `Names count to use static import with '*':` to `99`
- Sort `Import Layout` as the following:
    - `import all other imports`
    - `<blank line>`
    - `import javax.*`
    - `import java.*`
    - `<blank line>`
    - `import org.*`
    - `<blank line>`
    - `import com.*`
    - `<blank line>`
    - `import static all other imports`

# Apply on Netbeans
- Install `External code formatters` plugin.
- Open `Options`
- Navigate to `Editor` then `External Formatter`.
- Choose `Eclipse Java Code Formatter`.
- Import `codestyle.xml`
- Navigate to `Editor` then `Formatting`.
- Choose `Imports` from `Category`.
- Check `Class Count To Use Star Import` and modify text to `99`
- Check `Members Count To Use Static Star Import` and modify text to `99`
- Check `Separate Groups` and `Separate Static Imports` In `Import Layout` section
- Add and sort packages as the following:
    - `<all other imports>`
    - `javax`
    - `java`
    - `org`
    - `com`
    - `<all other imports>` Checked as `Static`

# Customized styles
- `org.eclipse.jdt.core.formatter.alignment_for_expressions_in_array_initializer` from `0` to `16`
- `org.eclipse.jdt.core.formatter.continuation_indentation` from `2` to `4`
- `org.eclipse.jdt.core.formatter.lineSplit` from `120` to `90`
- `org.eclipse.jdt.core.formatter.indentation.size` from `2` to `4`
- `org.eclipse.jdt.core.formatter.tabulation.size` from `2` to `4`
- `org.eclipse.jdt.core.formatter.blank_lines_after_imports` from `2` to `1`

# Resources
- Codestyle source: https://gobblin.readthedocs.io/en/latest/developer-guide/files/codestyle-eclipse.xml
- Guide: https://gobblin.readthedocs.io/en/latest/developer-guide/CodingStyle/