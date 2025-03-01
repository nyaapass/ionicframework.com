---
layout: "fluid/docs_base"
version: "3.9.2"
versionHref: "/docs"
path: ""
category: api
id: "button"
title: "Button"
header_sub_title: "Ionic API Documentation"
doc: "Button"
docType: "class"
show_preview_device: true
preview_device_url: "/docs/demos/src/button/www/"
angular_controller: APIDemoCtrl
---









<h1 class="api-title">
<a class="anchor" name="button" href="#button"></a>

Button
<h3><code>[ion-button]</code></h3>






</h1>

<a class="improve-v2-docs" href="http://github.com/ionic-team/ionic/edit/master/src/components/button/button.ts#L4">
改进这篇文档
</a>






<p>Buttons 是 Ionic 的简单组件。它们由文本和图标组成，并通过各种属性进行增强。</p>





<!-- @usage tag -->

<h2><a class="anchor" name="usage" href="#usage">用法</a></h2>

<pre><code class="lang-html">&lt;!-- 颜色 --&gt;
&lt;button ion-button&gt;Default&lt;/button&gt;

&lt;button ion-button color=&quot;secondary&quot;&gt;Secondary&lt;/button&gt;

&lt;button ion-button color=&quot;danger&quot;&gt;Danger&lt;/button&gt;

&lt;button ion-button color=&quot;light&quot;&gt;Light&lt;/button&gt;

&lt;button ion-button color=&quot;dark&quot;&gt;Dark&lt;/button&gt;

&lt;!-- 形状 --&gt;
&lt;button ion-button full&gt;Full Button&lt;/button&gt;

&lt;button ion-button block&gt;Block Button&lt;/button&gt;

&lt;button ion-button round&gt;Round Button&lt;/button&gt;

&lt;!-- 轮廓 --&gt;
&lt;button ion-button full outline&gt;Outline + Full&lt;/button&gt;

&lt;button ion-button block outline&gt;Outline + Block&lt;/button&gt;

&lt;button ion-button round outline&gt;Outline + Round&lt;/button&gt;

&lt;!-- 图标 --&gt;
&lt;button ion-button icon-start&gt;
  &lt;ion-icon name=&quot;star&quot;&gt;&lt;/ion-icon&gt;
  Left Icon
&lt;/button&gt;

&lt;button ion-button icon-end&gt;
  Right Icon
  &lt;ion-icon name=&quot;star&quot;&gt;&lt;/ion-icon&gt;
&lt;/button&gt;

&lt;button ion-button icon-only&gt;
  &lt;ion-icon name=&quot;star&quot;&gt;&lt;/ion-icon&gt;
&lt;/button&gt;

&lt;!-- 尺寸 --&gt;
&lt;button ion-button large&gt;Large&lt;/button&gt;

&lt;button ion-button&gt;Default&lt;/button&gt;

&lt;button ion-button small&gt;Small&lt;/button&gt;
</code></pre>




<!-- @property tags -->



<!-- instance methods on the class -->
<!-- input methods on the class -->
<h2><a class="anchor" name="input-properties" href="#input-properties">输入属性</a></h2>
<table class="table param-table" style="margin:0;">
  <thead>
    <tr>
      <th>属性</th>
      <th>类型</th>
      <th>详情</th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <td>block</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，就激活按钮的填充可用宽度样式。</p>
</td>
    </tr>

    <tr>
      <td>clear</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，就激活按钮的不带边框的透明样式。</p>
</td>
    </tr>

    <tr>
      <td>color</td>
      <td><code>string</code></td>
      <td><p> 从 Sass <code>$colors</code> 中映射的颜色。默认选项是： <code>&quot;primary&quot;</code>, <code>&quot;secondary&quot;</code>, <code>&quot;danger&quot;</code>, <code>&quot;light&quot;</code>, 和 <code>&quot;dark&quot;</code>。有关更多信息，请参阅 <a href="/docs/theming/theming-your-app">主题化你的应用</a>。</p>


</td>
    </tr>

    <tr>
      <td>default</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，则激活按钮的默认大小。通常是默认值，对 item 中的按钮有效。</p>
</td>
    </tr>

    <tr>
      <td>full</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，则激活按钮的填充可用宽度但无左右边框样式。</p>

</td>
    </tr>

    <tr>
      <td>large</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，则激活按钮的大尺寸样式。</p>
</td>
    </tr>

    <tr>
      <td>mode</td>
      <td><code>string</code></td>
      <td><p>决定使用哪种平台样式。可能的值是： <code>&quot;ios&quot;</code>, <code>&quot;md&quot;</code>, 或 <code>&quot;wp&quot;</code>。有关更多信息，请参阅<a href="/docs/theming/platform-specific-styles">平台样式</a>。</p>


</td>
    </tr>

    <tr>
      <td>outline</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，就激活按钮的带有边框的透明样式。</p>
</td>
    </tr>

    <tr>
      <td>round</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，就激活按钮的圆角样式。</p>
</td>
    </tr>

    <tr>
      <td>small</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true ，就激活按钮的小尺寸样式。</p>
</td>
    </tr>

    <tr>
      <td>solid</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，就激活按钮的固态（solid）样式。通常是默认值，对 toolbar 中的按钮很有用。</p>
</td>
    </tr>

    <tr>
      <td>strong</td>
      <td><code>boolean</code></td>
      <td><p>如果为 true，则激活按钮的字体较粗样式。</p>
</td>
    </tr>

  </tbody>
</table><h2><a class="anchor" name="advanced" href="#advanced">进阶</a></h2>
<pre><code class="lang-html">&lt;!-- 将 color 和 outline 输入属性绑定到表达式 --&gt;
&lt;button ion-button [color]=&quot;isDanger ? &#39;danger&#39; : &#39;primary&#39;&quot; [outline]=&quot;isOutline&quot;&gt;
  Danger (Solid)
&lt;/button&gt;

&lt;!-- 将 color 和 round 输入属性绑定到表达式 --&gt;
&lt;button ion-button [color]=&quot;myColor&quot; [round]=&quot;isRound&quot;&gt;
  Secondary (Round)
&lt;/button&gt;

&lt;!-- 将 color 和 clear 输入属性绑定到表达式 --&gt;
&lt;button ion-button [color]=&quot;isSecondary ? &#39;secondary&#39; : &#39;primary&#39;&quot;  [clear]=&quot;isClear&quot;&gt;
  Primary (Clear)
&lt;/button&gt;

&lt;!-- 将 color，outline 和 round 输入属性绑定到表达式 --&gt;
&lt;button ion-button [color]=&quot;myColor2&quot; [outline]=&quot;isOutline&quot; [round]=&quot;isRound&quot;&gt;
  Dark (Solid + Round)
&lt;/button&gt;

&lt;!-- 将 click 事件绑定到一个方法 --&gt;
&lt;button ion-button (click)=&quot;logEvent($event)&quot;&gt;
  Click me!
&lt;/button&gt;
</code></pre>
<pre><code class="lang-ts">@Component({
  templateUrl: &#39;main.html&#39;
})
class E2EPage {
  isDanger: boolean = true;
  isSecondary: boolean = false;
  isRound: boolean = true;
  isOutline: boolean = false;
  isClear: boolean = true;
  myColor: string = &#39;secondary&#39;;
  myColor2: string = &#39;dark&#39;;

  logEvent(event) {
    console.log(event)
  }
}
</code></pre>



  <h2 id="sass-variable-header"><a class="anchor" name="sass-variables" href="#sass-variables">Sass Variables</a></h2>
  <div id="sass-variables" ng-controller="SassToggleCtrl">
  <div class="sass-platform-toggle">



      <a ng-init="setSassPlatform('base')" ng-class="{ active: active === 'base' }" ng-click="setSassPlatform('base')" >All</a>



      <a ng-class="{ active: active === 'ios' }" ng-click="setSassPlatform('ios')">iOS</a>



      <a ng-class="{ active: active === 'md' }" ng-click="setSassPlatform('md')">Material Design</a>



      <a ng-class="{ active: active === 'wp' }" ng-click="setSassPlatform('wp')">Windows Platform</a>



  </div>



  <table ng-show="active === 'base'" id="sass-base" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>

      <tr>
        <td><code>$button-round-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-round-padding-end</code></td>

          <td><code>2.6rem</code></td>

        <td><p>Padding end of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-round-padding-bottom</code></td>

          <td><code>$button-round-padding-top</code></td>

        <td><p>Padding bottom of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-round-padding-start</code></td>

          <td><code>$button-round-padding-end</code></td>

        <td><p>Padding start of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-round-border-radius</code></td>

          <td><code>64px</code></td>

        <td><p>Border radius of the round button</p>
</td>
      </tr>

    </tbody>
  </table>

  <table ng-show="active === 'ios'" id="sass-ios" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>

      <tr>
        <td><code>$button-ios-margin-top</code></td>

          <td><code>.4rem</code></td>

        <td><p>Margin top of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-margin-end</code></td>

          <td><code>.2rem</code></td>

        <td><p>Margin end of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-margin-bottom</code></td>

          <td><code>.4rem</code></td>

        <td><p>Margin bottom of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-margin-start</code></td>

          <td><code>.2rem</code></td>

        <td><p>Margin start of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-padding-end</code></td>

          <td><code>1em</code></td>

        <td><p>Padding end of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-padding-bottom</code></td>

          <td><code>$button-ios-padding-top</code></td>

        <td><p>Padding bottom of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-padding-start</code></td>

          <td><code>$button-ios-padding-end</code></td>

        <td><p>Padding start of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-height</code></td>

          <td><code>2.8em</code></td>

        <td><p>Height of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-border-radius</code></td>

          <td><code>4px</code></td>

        <td><p>Border radius of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-font-size</code></td>

          <td><code>1.6rem</code></td>

        <td><p>Font size of the button text</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-background-color</code></td>

          <td><code>color($colors-ios, primary)</code></td>

        <td><p>Background color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-text-color</code></td>

          <td><code>color-contrast($colors-ios, $button-ios-background-color)</code></td>

        <td><p>Text color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-background-color-activated</code></td>

          <td><code>color-shade($button-ios-background-color)</code></td>

        <td><p>Background color of the activated button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-opacity-activated</code></td>

          <td><code>1</code></td>

        <td><p>Opacity of the activated button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-opacity-hover</code></td>

          <td><code>.8</code></td>

        <td><p>Opacity of the button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-large-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-large-padding-end</code></td>

          <td><code>1em</code></td>

        <td><p>Padding end of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-large-padding-bottom</code></td>

          <td><code>$button-ios-large-padding-top</code></td>

        <td><p>Padding bottom of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-large-padding-start</code></td>

          <td><code>$button-ios-large-padding-end</code></td>

        <td><p>Padding start of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-large-height</code></td>

          <td><code>2.8em</code></td>

        <td><p>Height of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-large-font-size</code></td>

          <td><code>2rem</code></td>

        <td><p>Font size of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-padding-end</code></td>

          <td><code>.9em</code></td>

        <td><p>Padding end of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-padding-bottom</code></td>

          <td><code>$button-ios-small-padding-top</code></td>

        <td><p>Padding bottom of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-padding-start</code></td>

          <td><code>$button-ios-small-padding-end</code></td>

        <td><p>Padding start of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-height</code></td>

          <td><code>2.1em</code></td>

        <td><p>Height of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-font-size</code></td>

          <td><code>1.3rem</code></td>

        <td><p>Font size of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-small-icon-font-size</code></td>

          <td><code>1.3em</code></td>

        <td><p>Font size of an icon in the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-border-width</code></td>

          <td><code>1px</code></td>

        <td><p>Border width of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-border-style</code></td>

          <td><code>solid</code></td>

        <td><p>Border style of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-border-radius</code></td>

          <td><code>$button-ios-border-radius</code></td>

        <td><p>Border radius of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-border-color</code></td>

          <td><code>$button-ios-background-color</code></td>

        <td><p>Border color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-text-color</code></td>

          <td><code>$button-ios-background-color</code></td>

        <td><p>Text color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-background-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-text-color-activated</code></td>

          <td><code>color-contrast($colors-ios, $button-ios-background-color)</code></td>

        <td><p>Text color of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-background-color-activated</code></td>

          <td><code>$button-ios-background-color</code></td>

        <td><p>Background color of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-outline-opacity-activated</code></td>

          <td><code>1</code></td>

        <td><p>Opacity of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-clear-border-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Border color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-clear-background-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-clear-background-color-activated</code></td>

          <td><code>$button-ios-clear-background-color</code></td>

        <td><p>Background color of the activated clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-clear-opacity-activated</code></td>

          <td><code>.4</code></td>

        <td><p>Opacity of the activated clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-clear-text-color-hover</code></td>

          <td><code>$button-ios-background-color</code></td>

        <td><p>Text color of the clear button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-clear-opacity-hover</code></td>

          <td><code>.6</code></td>

        <td><p>Opacity of the clear button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-round-padding-top</code></td>

          <td><code>$button-round-padding-top</code></td>

        <td><p>Padding top of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-round-padding-end</code></td>

          <td><code>$button-round-padding-end</code></td>

        <td><p>Padding end of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-round-padding-bottom</code></td>

          <td><code>$button-round-padding-bottom</code></td>

        <td><p>Padding bottom of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-round-padding-start</code></td>

          <td><code>$button-round-padding-start</code></td>

        <td><p>Padding start of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-round-border-radius</code></td>

          <td><code>$button-round-border-radius</code></td>

        <td><p>Border radius of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-ios-strong-font-weight</code></td>

          <td><code>600</code></td>

        <td><p>Font weight of the strong button</p>
</td>
      </tr>

    </tbody>
  </table>

  <table ng-show="active === 'md'" id="sass-md" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>

      <tr>
        <td><code>$button-md-margin-top</code></td>

          <td><code>.4rem</code></td>

        <td><p>Margin top of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-margin-end</code></td>

          <td><code>.2rem</code></td>

        <td><p>Margin end of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-margin-bottom</code></td>

          <td><code>.4rem</code></td>

        <td><p>Margin bottom of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-margin-start</code></td>

          <td><code>.2rem</code></td>

        <td><p>Margin start of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-padding-end</code></td>

          <td><code>1.1em</code></td>

        <td><p>Padding end of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-padding-bottom</code></td>

          <td><code>$button-md-padding-top</code></td>

        <td><p>Padding bottom of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-padding-start</code></td>

          <td><code>$button-md-padding-end</code></td>

        <td><p>Padding start of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-height</code></td>

          <td><code>3.6rem</code></td>

        <td><p>Height of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-border-radius</code></td>

          <td><code>2px</code></td>

        <td><p>Border radius of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-font-size</code></td>

          <td><code>1.4rem</code></td>

        <td><p>Font size of the button text</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-font-weight</code></td>

          <td><code>500</code></td>

        <td><p>Font weight of the button text</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-text-transform</code></td>

          <td><code>uppercase</code></td>

        <td><p>Capitalization of the button text</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-background-color</code></td>

          <td><code>color($colors-md, primary)</code></td>

        <td><p>Background color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-text-color</code></td>

          <td><code>color-contrast($colors-md, $button-md-background-color)</code></td>

        <td><p>Text color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-box-shadow</code></td>

          <td><code>0 2px 2px 0 rgba(0, 0, 0, .14), 0 3px 1px -2px rgba(0, 0, 0, .2), 0 1px 5px 0 rgba(0, 0, 0, .12)</code></td>

        <td><p>Box shadow of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-transition-duration</code></td>

          <td><code>300ms</code></td>

        <td><p>Duration of the transition of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-transition-timing-function</code></td>

          <td><code>cubic-bezier(.4, 0, .2, 1)</code></td>

        <td><p>Speed curve of the transition of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-background-color-hover</code></td>

          <td><code>$button-md-background-color</code></td>

        <td><p>Background color of the button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-background-color-activated</code></td>

          <td><code>color-shade($button-md-background-color)</code></td>

        <td><p>Background color of the activated button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-opacity-activated</code></td>

          <td><code>1</code></td>

        <td><p>Opacity of the activated button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-box-shadow-activated</code></td>

          <td><code>0 3px 5px rgba(0, 0, 0, .14), 0 3px 5px rgba(0, 0, 0, .21), 0 0 0 0 transparent</code></td>

        <td><p>Box shadow of the activated button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-ripple-background-color</code></td>

          <td><code>#555</code></td>

        <td><p>Background color of the ripple on the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-large-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-large-padding-end</code></td>

          <td><code>1em</code></td>

        <td><p>Padding end of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-large-padding-bottom</code></td>

          <td><code>$button-md-large-padding-top</code></td>

        <td><p>Padding bottom of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-large-padding-start</code></td>

          <td><code>$button-md-large-padding-end</code></td>

        <td><p>Padding start of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-large-height</code></td>

          <td><code>2.8em</code></td>

        <td><p>Height of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-large-font-size</code></td>

          <td><code>2rem</code></td>

        <td><p>Font size of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-padding-end</code></td>

          <td><code>.9em</code></td>

        <td><p>Padding end of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-padding-bottom</code></td>

          <td><code>$button-md-small-padding-top</code></td>

        <td><p>Padding bottom of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-padding-start</code></td>

          <td><code>$button-md-small-padding-end</code></td>

        <td><p>Padding start of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-height</code></td>

          <td><code>2.1em</code></td>

        <td><p>Height of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-font-size</code></td>

          <td><code>1.3rem</code></td>

        <td><p>Font size of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-small-icon-font-size</code></td>

          <td><code>1.4em</code></td>

        <td><p>Font size of an icon in the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-border-width</code></td>

          <td><code>1px</code></td>

        <td><p>Border width of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-border-style</code></td>

          <td><code>solid</code></td>

        <td><p>Border style of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-border-color</code></td>

          <td><code>$button-md-background-color</code></td>

        <td><p>Border color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-text-color</code></td>

          <td><code>$button-md-background-color</code></td>

        <td><p>Text color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-background-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-box-shadow</code></td>

          <td><code>none</code></td>

        <td><p>Box shadow of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-background-color-hover</code></td>

          <td><code>rgba(158, 158, 158, .1)</code></td>

        <td><p>Background color of the outline button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-background-color-activated</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-box-shadow-activated</code></td>

          <td><code>none</code></td>

        <td><p>Box shadow of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-opacity-activated</code></td>

          <td><code>1</code></td>

        <td><p>Opacity of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-outline-ripple-background-color</code></td>

          <td><code>$button-md-background-color</code></td>

        <td><p>Background color of the ripple on the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-border-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Border color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-text-color</code></td>

          <td><code>$button-md-background-color</code></td>

        <td><p>Text color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-background-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-box-shadow</code></td>

          <td><code>none</code></td>

        <td><p>Box shadow of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-opacity</code></td>

          <td><code>1</code></td>

        <td><p>Opacity of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-background-color-activated</code></td>

          <td><code>rgba(158, 158, 158, .2)</code></td>

        <td><p>Background color of the activated clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-box-shadow-activated</code></td>

          <td><code>$button-md-clear-box-shadow</code></td>

        <td><p>Box shadow of the activated clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-background-color-hover</code></td>

          <td><code>rgba(158, 158, 158, .1)</code></td>

        <td><p>Background color of the clear button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-clear-ripple-background-color</code></td>

          <td><code>#999</code></td>

        <td><p>Background color of the ripple on the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-round-padding-top</code></td>

          <td><code>$button-round-padding-top</code></td>

        <td><p>Padding top of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-round-padding-end</code></td>

          <td><code>$button-round-padding-end</code></td>

        <td><p>Padding end of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-round-padding-bottom</code></td>

          <td><code>$button-round-padding-bottom</code></td>

        <td><p>Padding bottom of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-round-padding-start</code></td>

          <td><code>$button-round-padding-start</code></td>

        <td><p>Padding start of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-round-border-radius</code></td>

          <td><code>$button-round-border-radius</code></td>

        <td><p>Border radius of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-md-strong-font-weight</code></td>

          <td><code>bold</code></td>

        <td><p>Font weight of the strong button</p>
</td>
      </tr>

    </tbody>
  </table>

  <table ng-show="active === 'wp'" id="sass-wp" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>

      <tr>
        <td><code>$button-wp-margin-top</code></td>

          <td><code>.4rem</code></td>

        <td><p>Margin top of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-margin-end</code></td>

          <td><code>.2rem</code></td>

        <td><p>Margin end of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-margin-bottom</code></td>

          <td><code>.4rem</code></td>

        <td><p>Margin bottom of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-margin-start</code></td>

          <td><code>.2rem</code></td>

        <td><p>Margin start of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-padding-end</code></td>

          <td><code>1.1em</code></td>

        <td><p>Padding end of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-padding-bottom</code></td>

          <td><code>$button-wp-padding-top</code></td>

        <td><p>Padding bottom of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-padding-start</code></td>

          <td><code>$button-wp-padding-end</code></td>

        <td><p>Padding start of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-height</code></td>

          <td><code>3.6rem</code></td>

        <td><p>Height of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-border-width</code></td>

          <td><code>3px</code></td>

        <td><p>Border width of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-border-style</code></td>

          <td><code>solid</code></td>

        <td><p>Border style of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-border-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Border color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-border-radius</code></td>

          <td><code>0</code></td>

        <td><p>Border radius of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-font-size</code></td>

          <td><code>1.4rem</code></td>

        <td><p>Font size of the button text</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-background-color</code></td>

          <td><code>color($colors-wp, primary)</code></td>

        <td><p>Background color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-text-color</code></td>

          <td><code>color-contrast($colors-wp, $button-wp-background-color)</code></td>

        <td><p>Text color of the button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-background-color-activated</code></td>

          <td><code>color-shade($button-wp-background-color)</code></td>

        <td><p>Background color of the activated button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-large-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-large-padding-end</code></td>

          <td><code>1em</code></td>

        <td><p>Padding end of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-large-padding-bottom</code></td>

          <td><code>$button-wp-large-padding-top</code></td>

        <td><p>Padding bottom of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-large-padding-start</code></td>

          <td><code>$button-wp-large-padding-end</code></td>

        <td><p>Padding start of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-large-height</code></td>

          <td><code>2.8em</code></td>

        <td><p>Height of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-large-font-size</code></td>

          <td><code>2rem</code></td>

        <td><p>Font size of the large button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-padding-top</code></td>

          <td><code>0</code></td>

        <td><p>Padding top of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-padding-end</code></td>

          <td><code>.9em</code></td>

        <td><p>Padding end of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-padding-bottom</code></td>

          <td><code>$button-wp-small-padding-top</code></td>

        <td><p>Padding bottom of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-padding-start</code></td>

          <td><code>$button-wp-small-padding-end</code></td>

        <td><p>Padding start of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-height</code></td>

          <td><code>2.1em</code></td>

        <td><p>Height of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-font-size</code></td>

          <td><code>1.3rem</code></td>

        <td><p>Font size of the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-small-icon-font-size</code></td>

          <td><code>1.4em</code></td>

        <td><p>Font size of an icon in the small button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-border-width</code></td>

          <td><code>1px</code></td>

        <td><p>Border width of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-border-style</code></td>

          <td><code>solid</code></td>

        <td><p>Border style of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-border-color</code></td>

          <td><code>$button-wp-background-color</code></td>

        <td><p>Border color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-text-color</code></td>

          <td><code>$button-wp-background-color</code></td>

        <td><p>Text color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-background-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-background-color-activated</code></td>

          <td><code>$button-wp-background-color</code></td>

        <td><p>Background color of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-outline-background-color-opacity-activated</code></td>

          <td><code>.16</code></td>

        <td><p>Opacity of the background color of the activated outline button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-clear-text-color</code></td>

          <td><code>$button-wp-background-color</code></td>

        <td><p>Text color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-clear-background-color</code></td>

          <td><code>transparent</code></td>

        <td><p>Background color of the clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-clear-background-color-activated</code></td>

          <td><code>rgba(158, 158, 158, .2)</code></td>

        <td><p>Background color of the activated clear button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-clear-background-color-hover</code></td>

          <td><code>rgba(158, 158, 158, .1)</code></td>

        <td><p>Background color of the clear button on hover</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-round-padding-top</code></td>

          <td><code>$button-round-padding-top</code></td>

        <td><p>Padding top of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-round-padding-end</code></td>

          <td><code>$button-round-padding-end</code></td>

        <td><p>Padding end of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-round-padding-bottom</code></td>

          <td><code>$button-round-padding-bottom</code></td>

        <td><p>Padding bottom of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-round-padding-start</code></td>

          <td><code>$button-round-padding-start</code></td>

        <td><p>Padding start of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-round-border-radius</code></td>

          <td><code>$button-round-border-radius</code></td>

        <td><p>Border radius of the round button</p>
</td>
      </tr>

      <tr>
        <td><code>$button-wp-strong-font-weight</code></td>

          <td><code>bold</code></td>

        <td><p>Font weight of the strong button</p>
</td>
      </tr>

    </tbody>
  </table>

</div>



<!-- related link -->

<h2><a class="anchor" name="related" href="#related">Related</a></h2>

<a href="/docs/components#buttons">Button Component Docs</a>,
<a href="/docs/components#fabs">FabButton Docs</a>,
<a href="../../fab/FabButton">FabButton API Docs</a>,
<a href="../../fab/FabContainer">FabContainer API Docs</a><!-- end content block -->


<!-- end body block -->

