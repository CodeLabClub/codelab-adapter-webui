# CodeLab Adapter Web UI
CodeLab Adapter v2决定采用Web UI。

Web 技术的跨平台能力是最好的，而且基于 html 和 css 的布局技术，足够简单和灵活，所以我们最终决定采用 Web UI 作为默认的 UI。由于 Web 开发者众多，也方便更多开发者能参与进来改进它。

我们前两个版本的UI分别基于 Tkinter 和 PyQt5, 参考:[CodeLab Adapter v2#使用 web UI](https://www.codelab.club/blog/codelab-adapter-v2/#使用-web-ui)

# 现状
目前我们已经给出了极简版的 demo UI， 只用到了 HTML

<img width=300 src="http://wwj-fig-bed.just4fun.site/webui_0cdd2618.png"  />

通过修改和替换`~/codelab_adapter/src/webui.html`, 你可以使用任何主题的Web UI。

我将当前的Web UI从源码中分离一份到这儿: webui.html(纯前端)，方便社区web开发者据此设计出好看的UI。

# 目标
设计出简约、美观、实用的Web UI。

# 限制条件
在可能的情况下，最好能做到:

*  使用Vuejs构建界面逻辑
*  使用轻量级的UI库。

