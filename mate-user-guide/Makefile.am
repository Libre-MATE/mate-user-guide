@YELP_HELP_RULES@

HELP_ID = mate-user-guide
HELP_FILES = index.docbook	\
	legal.xml		\
	gosbasic.xml		\
	goscustdesk.xml		\
	goseditmainmenu.xml	\
	goscaja.xml		\
	gosoverview.xml		\
	gospanel.xml		\
	gosstartsession.xml	\
	gostools.xml		\
	gosdconf.xml		\
	gosdconfkeys.xml	\
	gosfeedback.xml		\
	glossary.xml

HELP_MEDIA = \
	figures/ask_pointer.png \
	figures/busy_pointer.png \
	figures/caja_always_use_browser.png \
	figures/caja_browser_mode.png \
	figures/caja_button_bar.png \
	figures/caja_emblem.png \
	figures/caja_go_to_location.png \
	figures/caja_link_emblem.png \
	figures/caja_noread_emblem.png \
	figures/caja_normal_size_button.png \
	figures/caja_nowrite_emblem.png \
	figures/caja_refine_search.png \
	figures/caja_restore_saved_search.png \
	figures/caja_search_bar.png \
	figures/caja_search_results.png \
	figures/caja_spatial_icon_view.png \
	figures/caja_spatial_list_view.png \
	figures/caja_spatial_mode.png \
	figures/caja_spatial_view.png \
	figures/caja_trash_launcher.png \
	figures/caja_zoom_in_button.png \
	figures/caja_zoom_out_button.png \
	figures/copy_pointer.png \
	figures/force_quit.png \
	figures/four_hide_button.png \
	figures/hyperlink_pointer.png \
	figures/ibeam_pointer.png \
	figures/link_pointer.png \
	figures/lockscreen_icon.png \
	figures/logout_icon.png \
	figures/menu_bar_applet.png \
	figures/move_panel_object_pointer.png \
	figures/move_pointer.png \
	figures/movewindow_pointer.png \
	figures/normal_pointer.png \
	figures/not_available_pointer.png \
	figures/notification_area_icon.png \
	figures/open_drawer.png \
	figures/openwindows_menu.png \
	figures/org_mate_desktop_background_logical_view.png \
	figures/org_mate_desktop_background_only_logical_view.png \
	figures/panel_object_popup_menu.png \
	figures/picture_filename_dconf_key_edit.png \
	figures/picture_filename_dconf_key_view.png \
	figures/resize_pointer.png \
	figures/run_button.png \
	figures/sample_applet.png \
	figures/searchtool_button.png \
	figures/show_desktop_button.png \
	figures/titlebar_window.png \
	figures/workspace_switcher_applet.png \
	figures/yelp_add_bookmark.png \
	figures/yelp_edit_bookmarks.png \
	figures/yelp_preferences.png \
	figures/yelp_window.png

if USE_NLS
# Add linguas to be ignored, e.g. IGNORE_HELP_LINGUAS = ca de es fr
IGNORE_HELP_LINGUAS =
HELP_LINGUAS = $(if $(IGNORE_HELP_LINGUAS), \
	$(filter-out $(IGNORE_HELP_LINGUAS),$(subst /,,$(dir $(wildcard */*.po)))), \
	$(subst /,,$(dir $(wildcard */*.po))) )
else
HELP_LINGUAS =
endif

-include $(top_srcdir)/git.mk

-include $(top_srcdir)/git.mk
