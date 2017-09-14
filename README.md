# ifmo_I_intro
исследование в области веб-языков и моделирования ИС

Адрес текста ЛР:
https://kodaktor.ru/08092017

C9 : https://c9.io/icqking

Попытка ответа на вопрос:
  DTD - Document Type Definition.
  Это инструкция браузера о версии языка данной страницы. DTD указывается перед тегом <html>. В DTD не задается контекстно-свободная грамматика (грамматика, у которой в левых частях всех правил стоят только одиночные нетерминальные символы).
  DTD нужен для того, чтобы браузер правильно понимал как отоброжать HTML документ. В HTML существует несколько видов DTD:
	- строгий. HTML документы со строгоим DTD могут содержать все HTML элементы и атрибуты, кроме презентационных и устаревших. Использование фреймов запрещено.
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
	- переходный. HTML документ с переходным DTD могут содержать все HTML элементы и атрибуты включая презентационные и устаревшие. Использование фреймов запрещено.
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
	- фреймовые. HTML документы с фреймовым DTD могут содержать все HTML элементы и атрибуты включая презентационные и устаревшие. Использование фреймов разрешено.
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
	- HTML5 DOCTYPE. В HTML5 вместо трех различных Doctype был введен один универсальный.
		<!DOCTYPE html>.

  Определение HTML задется в формате DTD. Он используется для формализации языков семейства SGML. Этот формат содержит определения всех доступных элементов, их атрибутов и иерархии.
  Синтаксис HTML5 не базируется на SGML, несмотря на подобие его разметки. HTML5 не имеет ссылку на DTD файл.
  HTML4 базируется на SGML и XHTML. HTML5 новое поколение HTML, замена для HTML4.
  По идее HTML5 не имеет ничего общего с DTD.
